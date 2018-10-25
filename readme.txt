git安装：
	直接默认安装即可
	最好在Notepad++中设置UTF-8无BOM格式编码  新建.txt,否则编码易出现问题
	
	mac直接git --version看看是否有默认git，若没有brew install git 
	which git查找git文件夹
	安装完成后，还需要最后一步设置，在命令行输入：
	$ git config --global user.name "Your Name"
	$ git config --global user.email "email@example.com"
	
	git命令
	
	1、mkdir filename  新建文件
	2、cd filename 进入文件
	3、pwd 显示当前目录
	4、git init  git仓库建立
	5、ls -ah 显示.git目录
	
	注：在目录文件夹中新建、添加、修改东西
	
	6、git add file或者. 把文件添加到仓库（可file1 file2）
	7、git commit -m "版本注释" 
	8、git status 时刻掌握仓库当前状态
	9、git diff file 查看有修改状态的文件的修改部分的difference	
	10、git log  从最近到最远的提交日志（--pretty=oneline 添加版本号）
	11、$ git reset --hard HEAD^(HEAD是当前版本号，可以此向上查找版本号)  
		回退到上一个版本（$ git reset --hard 3628164），Git的版本回退速度非常快
		用git diff HEAD -- readme.txt命令可以查看工作区和版本库里面最新版本的区别
	12、$ cat readme.txt  看看readme.txt的内容
	13、git reflog 查看历史命令
	
	14、git checkout -- readme.txt(filename)  丢弃工作区的修改
			一种没放入暂存区，撤销修改就回到和版本库一模一样的状态；
			一种已添加到暂存区，又做了修改，撤销修改就回到添加到暂存区后的状态
			即 让这个文件回到最近一次git commit或git add时的状态。
			
	15、改乱了工作区某文件，想直接丢弃工作区修改  git checkout -- file	
	16、改乱了工作区文件内容，并且添加到缓存区，想丢弃修改  git reset HEAD file  然后git checkout -- file	
	
	建立远程链接
	
	1、创建SSH Key (申请GitHub账号)
		$ ssh-keygen -t rsa -C "527510567@qq.com"    生成文件.ssh，获得本机ssh keygen  在github中设置ssh时，key为id_rsa.pub中内容，私钥id_rsa不能泄露
	
	2、进入GitHub--setting--ssh key  titile——随便   key————粘贴id_rsa.pub中内容
	
	3、GitHub————右上角“create a new repo”	
	
	4、已有仓库和本地仓库关联，把本地仓库内容推送到GitHub(关联远程库) 
		git remote add origin git@github.com:liuyange/bsgrid.git(即你GitHub仓库的账户名)
		
	5、第一次推送master分支，加上-u，不但把本地分支内容推送到远程新的master分支，还把本地的master分支和远程master分支关联起来
		git push -u origin master(之后再提交则为 git push origin master)
	
	注：第一次使用git的clone或push命令链接GitHub时，会报警告
		The authenticity of host 'github.com (xx.xx.xx.xx)' can't be established.
		RSA key fingerprint is xx.xx.xx.xx.xx.
		Are you sure you want to continue connecting (yes/no)?
		
		yes之后按回车即可，git会输出一个警告，告诉你已经把GitHub的key添加到本机的一个信任列表了，
		Warning: Permanently added 'github.com' (RSA) to the list of known hosts.
	
	简单方法：
		先GitHub上建立项目、文件，git clone git@github.com:liuyange/bsgrid.git克隆项目到本地，
		cd bsgrid
		ls即可看到项目中内容
		git clone可是https://github.com/michaelliao/gitskills.git地址
		git支持https、ssh，但是ssh支持的原生git协议速度最快
	
	创建并合并分支
		git主分支叫master分支，HEAD---指向master，master---指向提交，HEAD指向当前分支
		创建新分支dev，新指针dev指向master相同的提交，HEAD指向dev就表示当前分支在dev上
		此时改变的时dev分支，master分支无变化，完成修改后把dev合并到master上即可，最简单方式是：
		直接把master指向dev的当前提交。
		合并完成后，直接删除dev分支就把dev指针删掉了，只留主分支master
		1----创建dev分支并切换到dev分支：git checkout -b dev(git branch dev    git checkout dev)
		2----git branch查看当前分支：git branch（当前分支前*）
		3----当前分支操作：git add readme.txt   git commit -m "branch dev change"
		4----dev工作完成，切换回master分支：git checkout master
		5----把dev分支内容合并到master：git merge dev
		6----合并完成，删除dev分支：git branch -d dev
		7----查看当前分支：git branch（只剩下master分支了）
		
		注：查看修改文件内容：vi filename，如果冲突了，在文件中合并内容重新上传即可
			git log --graph命令可以看到分支合并图（git log --graph --pretty=oneline --abbrev-commit）
			
			
	分支管理策略
		Fast Forward模式下删除分支就丢掉分支信息，我们实战--no-ff方式的git merge
			1--- git checkout -b dev
			2--- git add readme.txt
			3--- git commit -m "注解"
			4--- git checkout master 
			5--- git merge --no-ff -m "merge with no-ff" dev
			6--- git log --graph --pretty=oneline --abbrev-commit合并后查看分支历史
			
		合并分支时，加上--no-ff参数就可以用普通模式合并，合并后的历史有分支，
		能看出来曾经做过合并，而fast forward合并就看不出来曾经做过合并	
			7--- git stash	当前工作现场“储藏”起来，等以后恢复现场后继续工作
			8--- 确定在哪个分支上修复bug  git checkout -b issue-101	
			9--- 修复bug，上传 git add name  git commit -m "fixed"
			10--- git checkout master 	
			11--- git merge --no-ff -m "merged bug fix 101" issue-101    
				  git branch -d issue-101
				  git checkout dev回dev分支继续工作
			12--- git status 工作区时干净的
			      git stash list 工作区在，但需要恢复
					  一：git stash apply  然后 git stash drop 来删除stash内容
					  二：git stash pop 恢复同时删除
				  git stash list查看，就看不到任何stash内容了
            13--- 要丢弃一个没有被合并过的分支，git branch -D feature-vulcan 
			
			master分支是主分支，因此要时刻与远程同步；
			$ git push origin master
			
			dev分支是开发分支，团队所有成员都需要在上面工作，所以也需要与远程同步；
			如果要推送其他分支，比如dev，就改成：
			$ git push origin dev
		
		git status
		git add hello.txt
		git commit -m "one change"
		git push origin dev
		冲突：
		git pull
		仍有问题,没有指定本地dev分支与远程origin/dev分支的链接.建立本地分支和远程分支的关联:
		git branch --set-upstream dev origin/dev
		git pull
		手动修改冲突，提交即可add commit  git push origin dev
	
	标签管理
		发布一个版本时，我们通常先在版本库中打一个标签（tag）
		tag就是一个让人容易记住的有意义的名字，它跟某个commit绑在一起。
		git branch 
		git checkout master
		git tag v1.0 即可打上一个新标签
		git tag查看所有标签
		找到历史提交的commit id，就可以打上了
		git log --pretty=oneline --addrev-commit
		对应commit id：
		git tag v0.9 6224937
		标签不是按时间顺序列出，而是按字母排序的
		git show v0.9
		还可以创建带有说明的标签，用-a指定标签名，-m指定说明文字：
		$ git tag -a v0.1 -m "version 0.1 released" 3628164
		删除：
		$ git tag -d v0.1
		推送某个标签到远程
		$ git push origin v1.0
		一次性推送全部尚未推送到远程的本地标签：
		git push origin --tags
		先从本地删除：
		$ git tag -d v0.9
		从远程删除:
		$ git push origin :refs/tags/v0.9
一个更简单方便的方法是使用sourcetree,非常适合多人合作



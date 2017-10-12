{\rtf1\ansi\ansicpg936\cocoartf1561
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset134 PingFangSC-Regular;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 git
\f1 \'b0\'b2\'d7\'b0\'a3\'ba
\f0 \
	
\f1 \'d6\'b1\'bd\'d3\'c4\'ac\'c8\'cf\'b0\'b2\'d7\'b0\'bc\'b4\'bf\'c9
\f0 \
	
\f1 \'d7\'ee\'ba\'c3\'d4\'da
\f0 Notepad++
\f1 \'d6\'d0\'c9\'e8\'d6\'c3
\f0 UTF-8
\f1 \'ce\'de
\f0 BOM
\f1 \'b8\'f1\'ca\'bd\'b1\'e0\'c2\'eb
\f0   
\f1 \'d0\'c2\'bd\'a8
\f0 .txt,
\f1 \'b7\'f1\'d4\'f2\'b1\'e0\'c2\'eb\'d2\'d7\'b3\'f6\'cf\'d6\'ce\'ca\'cc\'e2
\f0 \
	\
	mac
\f1 \'d6\'b1\'bd\'d3
\f0 git --version
\f1 \'bf\'b4\'bf\'b4\'ca\'c7\'b7\'f1\'d3\'d0\'c4\'ac\'c8\'cf
\f0 git
\f1 \'a3\'ac\'c8\'f4\'c3\'bb\'d3\'d0
\f0 brew install git \
	which git
\f1 \'b2\'e9\'d5\'d2
\f0 git
\f1 \'ce\'c4\'bc\'fe\'bc\'d0
\f0 \
	
\f1 \'b0\'b2\'d7\'b0\'cd\'ea\'b3\'c9\'ba\'f3\'a3\'ac\'bb\'b9\'d0\'e8\'d2\'aa\'d7\'ee\'ba\'f3\'d2\'bb\'b2\'bd\'c9\'e8\'d6\'c3\'a3\'ac\'d4\'da\'c3\'fc\'c1\'ee\'d0\'d0\'ca\'e4\'c8\'eb\'a3\'ba
\f0 \
	$ git config --global user.name "Your Name"\
	$ git config --global user.email "email@example.com"\
	\
	git
\f1 \'c3\'fc\'c1\'ee
\f0 \
	\
	1
\f1 \'a1\'a2
\f0 mkdir filename  
\f1 \'d0\'c2\'bd\'a8\'ce\'c4\'bc\'fe
\f0 \
	2
\f1 \'a1\'a2
\f0 cd filename 
\f1 \'bd\'f8\'c8\'eb\'ce\'c4\'bc\'fe
\f0 \
	3
\f1 \'a1\'a2
\f0 pwd 
\f1 \'cf\'d4\'ca\'be\'b5\'b1\'c7\'b0\'c4\'bf\'c2\'bc
\f0 \
	4
\f1 \'a1\'a2
\f0 git init  git
\f1 \'b2\'d6\'bf\'e2\'bd\'a8\'c1\'a2
\f0 \
	5
\f1 \'a1\'a2
\f0 ls -ah 
\f1 \'cf\'d4\'ca\'be
\f0 .git
\f1 \'c4\'bf\'c2\'bc
\f0 \
	\
	
\f1 \'d7\'a2\'a3\'ba\'d4\'da\'c4\'bf\'c2\'bc\'ce\'c4\'bc\'fe\'bc\'d0\'d6\'d0\'d0\'c2\'bd\'a8\'a1\'a2\'cc\'ed\'bc\'d3\'a1\'a2\'d0\'de\'b8\'c4\'b6\'ab\'ce\'f7
\f0 \
	\
	6
\f1 \'a1\'a2
\f0 git add file
\f1 \'bb\'f2\'d5\'df
\f0 . 
\f1 \'b0\'d1\'ce\'c4\'bc\'fe\'cc\'ed\'bc\'d3\'b5\'bd\'b2\'d6\'bf\'e2\'a3\'a8\'bf\'c9
\f0 file1 file2
\f1 \'a3\'a9
\f0 \
	7
\f1 \'a1\'a2
\f0 git commit -m "
\f1 \'b0\'e6\'b1\'be\'d7\'a2\'ca\'cd
\f0 " \
	8
\f1 \'a1\'a2
\f0 git status 
\f1 \'ca\'b1\'bf\'cc\'d5\'c6\'ce\'d5\'b2\'d6\'bf\'e2\'b5\'b1\'c7\'b0\'d7\'b4\'cc\'ac
\f0 \
	9
\f1 \'a1\'a2
\f0 git diff file 
\f1 \'b2\'e9\'bf\'b4\'d3\'d0\'d0\'de\'b8\'c4\'d7\'b4\'cc\'ac\'b5\'c4\'ce\'c4\'bc\'fe\'b5\'c4\'d0\'de\'b8\'c4\'b2\'bf\'b7\'d6\'b5\'c4
\f0 difference	\
	10
\f1 \'a1\'a2
\f0 git log  
\f1 \'b4\'d3\'d7\'ee\'bd\'fc\'b5\'bd\'d7\'ee\'d4\'b6\'b5\'c4\'cc\'e1\'bd\'bb\'c8\'d5\'d6\'be\'a3\'a8
\f0 --pretty=oneline 
\f1 \'cc\'ed\'bc\'d3\'b0\'e6\'b1\'be\'ba\'c5\'a3\'a9
\f0 \
	11
\f1 \'a1\'a2
\f0 $ git reset --hard HEAD^(HEAD
\f1 \'ca\'c7\'b5\'b1\'c7\'b0\'b0\'e6\'b1\'be\'ba\'c5\'a3\'ac\'bf\'c9\'d2\'d4\'b4\'cb\'cf\'f2\'c9\'cf\'b2\'e9\'d5\'d2\'b0\'e6\'b1\'be\'ba\'c5
\f0 )  \
		
\f1 \'bb\'d8\'cd\'cb\'b5\'bd\'c9\'cf\'d2\'bb\'b8\'f6\'b0\'e6\'b1\'be\'a3\'a8
\f0 $ git reset --hard 3628164
\f1 \'a3\'a9\'a3\'ac
\f0 Git
\f1 \'b5\'c4\'b0\'e6\'b1\'be\'bb\'d8\'cd\'cb\'cb\'d9\'b6\'c8\'b7\'c7\'b3\'a3\'bf\'ec
\f0 \
		
\f1 \'d3\'c3
\f0 git diff HEAD -- readme.txt
\f1 \'c3\'fc\'c1\'ee\'bf\'c9\'d2\'d4\'b2\'e9\'bf\'b4\'b9\'a4\'d7\'f7\'c7\'f8\'ba\'cd\'b0\'e6\'b1\'be\'bf\'e2\'c0\'ef\'c3\'e6\'d7\'ee\'d0\'c2\'b0\'e6\'b1\'be\'b5\'c4\'c7\'f8\'b1\'f0
\f0 \
	12
\f1 \'a1\'a2
\f0 $ cat readme.txt  
\f1 \'bf\'b4\'bf\'b4
\f0 readme.txt
\f1 \'b5\'c4\'c4\'da\'c8\'dd
\f0 \
	13
\f1 \'a1\'a2
\f0 git reflog 
\f1 \'b2\'e9\'bf\'b4\'c0\'fa\'ca\'b7\'c3\'fc\'c1\'ee
\f0 \
	\
	14
\f1 \'a1\'a2
\f0 git checkout -- readme.txt(filename)  
\f1 \'b6\'aa\'c6\'fa\'b9\'a4\'d7\'f7\'c7\'f8\'b5\'c4\'d0\'de\'b8\'c4
\f0 \
			
\f1 \'d2\'bb\'d6\'d6\'c3\'bb\'b7\'c5\'c8\'eb\'d4\'dd\'b4\'e6\'c7\'f8\'a3\'ac\'b3\'b7\'cf\'fa\'d0\'de\'b8\'c4\'be\'cd\'bb\'d8\'b5\'bd\'ba\'cd\'b0\'e6\'b1\'be\'bf\'e2\'d2\'bb\'c4\'a3\'d2\'bb\'d1\'f9\'b5\'c4\'d7\'b4\'cc\'ac\'a3\'bb
\f0 \
			
\f1 \'d2\'bb\'d6\'d6\'d2\'d1\'cc\'ed\'bc\'d3\'b5\'bd\'d4\'dd\'b4\'e6\'c7\'f8\'a3\'ac\'d3\'d6\'d7\'f6\'c1\'cb\'d0\'de\'b8\'c4\'a3\'ac\'b3\'b7\'cf\'fa\'d0\'de\'b8\'c4\'be\'cd\'bb\'d8\'b5\'bd\'cc\'ed\'bc\'d3\'b5\'bd\'d4\'dd\'b4\'e6\'c7\'f8\'ba\'f3\'b5\'c4\'d7\'b4\'cc\'ac
\f0 \
			
\f1 \'bc\'b4
\f0  
\f1 \'c8\'c3\'d5\'e2\'b8\'f6\'ce\'c4\'bc\'fe\'bb\'d8\'b5\'bd\'d7\'ee\'bd\'fc\'d2\'bb\'b4\'ce
\f0 git commit
\f1 \'bb\'f2
\f0 git add
\f1 \'ca\'b1\'b5\'c4\'d7\'b4\'cc\'ac\'a1\'a3
\f0 \
			\
	15
\f1 \'a1\'a2\'b8\'c4\'c2\'d2\'c1\'cb\'b9\'a4\'d7\'f7\'c7\'f8\'c4\'b3\'ce\'c4\'bc\'fe\'a3\'ac\'cf\'eb\'d6\'b1\'bd\'d3\'b6\'aa\'c6\'fa\'b9\'a4\'d7\'f7\'c7\'f8\'d0\'de\'b8\'c4
\f0   git checkout -- file	\
	16
\f1 \'a1\'a2\'b8\'c4\'c2\'d2\'c1\'cb\'b9\'a4\'d7\'f7\'c7\'f8\'ce\'c4\'bc\'fe\'c4\'da\'c8\'dd\'a3\'ac\'b2\'a2\'c7\'d2\'cc\'ed\'bc\'d3\'b5\'bd\'bb\'ba\'b4\'e6\'c7\'f8\'a3\'ac\'cf\'eb\'b6\'aa\'c6\'fa\'d0\'de\'b8\'c4
\f0   git reset HEAD file  
\f1 \'c8\'bb\'ba\'f3
\f0 git checkout -- file	\
	\
	
\f1 \'bd\'a8\'c1\'a2\'d4\'b6\'b3\'cc\'c1\'b4\'bd\'d3
\f0 \
	\
	1
\f1 \'a1\'a2\'b4\'b4\'bd\'a8
\f0 SSH Key (
\f1 \'c9\'ea\'c7\'eb
\f0 GitHub
\f1 \'d5\'cb\'ba\'c5
\f0 )\
		$ ssh-keygen -t rsa -C "527510567@qq.com"    
\f1 \'c9\'fa\'b3\'c9\'ce\'c4\'bc\'fe.ssh\'a3\'ac\'bb\'f1\'b5\'c3\'b1\'be\'bb\'fa
\f0 ssh keygen  
\f1 \'d4\'da
\f0 github
\f1 \'d6\'d0\'c9\'e8\'d6\'c3
\f0 ssh
\f1 \'ca\'b1\'a3\'ac
\f0 key
\f1 \'ce\'aa
\f0 id_rsa.pub
\f1 \'d6\'d0\'c4\'da\'c8\'dd\'a3\'ac\'cb\'bd\'d4\'bf
\f0 id_rsa
\f1 \'b2\'bb\'c4\'dc\'d0\'b9\'c2\'b6
\f0 \
	\
	2
\f1 \'a1\'a2\'bd\'f8\'c8\'eb
\f0 GitHub--setting--ssh key  titile\'97\'97
\f1 \'cb\'e6\'b1\'e3
\f0    key\'97\'97\'97\'97
\f1 \'d5\'b3\'cc\'f9
\f0 id_rsa.pub
\f1 \'d6\'d0\'c4\'da\'c8\'dd
\f0 \
	\
	3
\f1 \'a1\'a2
\f0 GitHub\'97\'97\'97\'97
\f1 \'d3\'d2\'c9\'cf\'bd\'c7
\f0 \'93create a new repo\'94	\
	\
	4
\f1 \'a1\'a2\'d2\'d1\'d3\'d0\'b2\'d6\'bf\'e2\'ba\'cd\'b1\'be\'b5\'d8\'b2\'d6\'bf\'e2\'b9\'d8\'c1\'aa\'a3\'ac\'b0\'d1\'b1\'be\'b5\'d8\'b2\'d6\'bf\'e2\'c4\'da\'c8\'dd\'cd\'c6\'cb\'cd\'b5\'bd
\f0 GitHub(
\f1 \'b9\'d8\'c1\'aa\'d4\'b6\'b3\'cc\'bf\'e2
\f0 ) \
		git remote add origin git@github.com:liuyange/bsgrid.git(
\f1 \'bc\'b4\'c4\'e3
\f0 GitHub
\f1 \'b2\'d6\'bf\'e2\'b5\'c4\'d5\'cb\'bb\'a7\'c3\'fb
\f0 )\
		\
	5
\f1 \'a1\'a2\'b5\'da\'d2\'bb\'b4\'ce\'cd\'c6\'cb\'cd
\f0 master
\f1 \'b7\'d6\'d6\'a7\'a3\'ac\'bc\'d3\'c9\'cf
\f0 -u
\f1 \'a3\'ac\'b2\'bb\'b5\'ab\'b0\'d1\'b1\'be\'b5\'d8\'b7\'d6\'d6\'a7\'c4\'da\'c8\'dd\'cd\'c6\'cb\'cd\'b5\'bd\'d4\'b6\'b3\'cc\'d0\'c2\'b5\'c4
\f0 master
\f1 \'b7\'d6\'d6\'a7\'a3\'ac\'bb\'b9\'b0\'d1\'b1\'be\'b5\'d8\'b5\'c4
\f0 master
\f1 \'b7\'d6\'d6\'a7\'ba\'cd\'d4\'b6\'b3\'cc
\f0 master
\f1 \'b7\'d6\'d6\'a7\'b9\'d8\'c1\'aa\'c6\'f0\'c0\'b4
\f0 \
		git push -u origin master(
\f1 \'d6\'ae\'ba\'f3\'d4\'d9\'cc\'e1\'bd\'bb\'d4\'f2\'ce\'aa
\f0  git push origin master)\
	\
	
\f1 \'d7\'a2\'a3\'ba\'b5\'da\'d2\'bb\'b4\'ce\'ca\'b9\'d3\'c3
\f0 git
\f1 \'b5\'c4
\f0 clone
\f1 \'bb\'f2
\f0 push
\f1 \'c3\'fc\'c1\'ee\'c1\'b4\'bd\'d3
\f0 GitHub
\f1 \'ca\'b1\'a3\'ac\'bb\'e1\'b1\'a8\'be\'af\'b8\'e6
\f0 \
		The authenticity of host 'github.com (xx.xx.xx.xx)' can't be established.\
		RSA key fingerprint is xx.xx.xx.xx.xx.\
		Are you sure you want to continue connecting (yes/no)?\
		\
		yes
\f1 \'d6\'ae\'ba\'f3\'b0\'b4\'bb\'d8\'b3\'b5\'bc\'b4\'bf\'c9\'a3\'ac
\f0 git
\f1 \'bb\'e1\'ca\'e4\'b3\'f6\'d2\'bb\'b8\'f6\'be\'af\'b8\'e6\'a3\'ac\'b8\'e6\'cb\'df\'c4\'e3\'d2\'d1\'be\'ad\'b0\'d1
\f0 GitHub
\f1 \'b5\'c4
\f0 key
\f1 \'cc\'ed\'bc\'d3\'b5\'bd\'b1\'be\'bb\'fa\'b5\'c4\'d2\'bb\'b8\'f6\'d0\'c5\'c8\'ce\'c1\'d0\'b1\'ed\'c1\'cb\'a3\'ac
\f0 \
		Warning: Permanently added 'github.com' (RSA) to the list of known hosts.\
	\
	
\f1 \'bc\'f2\'b5\'a5\'b7\'bd\'b7\'a8\'a3\'ba
\f0 \
		
\f1 \'cf\'c8
\f0 GitHub
\f1 \'c9\'cf\'bd\'a8\'c1\'a2\'cf\'ee\'c4\'bf\'a1\'a2\'ce\'c4\'bc\'fe\'a3\'ac
\f0 git clone git@github.com:liuyange/bsgrid.git
\f1 \'bf\'cb\'c2\'a1\'cf\'ee\'c4\'bf\'b5\'bd\'b1\'be\'b5\'d8\'a3\'ac
\f0 \
		cd bsgrid\
		ls
\f1 \'bc\'b4\'bf\'c9\'bf\'b4\'b5\'bd\'cf\'ee\'c4\'bf\'d6\'d0\'c4\'da\'c8\'dd
\f0 \
		git clone
\f1 \'bf\'c9\'ca\'c7
\f0 https://github.com/michaelliao/gitskills.git
\f1 \'b5\'d8\'d6\'b7
\f0 \
		git
\f1 \'d6\'a7\'b3\'d6
\f0 https
\f1 \'a1\'a2
\f0 ssh
\f1 \'a3\'ac\'b5\'ab\'ca\'c7
\f0 ssh
\f1 \'d6\'a7\'b3\'d6\'b5\'c4\'d4\'ad\'c9\'fa
\f0 git
\f1 \'d0\'ad\'d2\'e9\'cb\'d9\'b6\'c8\'d7\'ee\'bf\'ec
\f0 \
	\
	
\f1 \'b4\'b4\'bd\'a8\'b2\'a2\'ba\'cf\'b2\'a2\'b7\'d6\'d6\'a7
\f0 \
		git
\f1 \'d6\'f7\'b7\'d6\'d6\'a7\'bd\'d0
\f0 master
\f1 \'b7\'d6\'d6\'a7\'a3\'ac
\f0 HEAD---
\f1 \'d6\'b8\'cf\'f2
\f0 master
\f1 \'a3\'ac
\f0 master---
\f1 \'d6\'b8\'cf\'f2\'cc\'e1\'bd\'bb\'a3\'ac
\f0 HEAD
\f1 \'d6\'b8\'cf\'f2\'b5\'b1\'c7\'b0\'b7\'d6\'d6\'a7
\f0 \
		
\f1 \'b4\'b4\'bd\'a8\'d0\'c2\'b7\'d6\'d6\'a7
\f0 dev
\f1 \'a3\'ac\'d0\'c2\'d6\'b8\'d5\'eb
\f0 dev
\f1 \'d6\'b8\'cf\'f2
\f0 master
\f1 \'cf\'e0\'cd\'ac\'b5\'c4\'cc\'e1\'bd\'bb\'a3\'ac
\f0 HEAD
\f1 \'d6\'b8\'cf\'f2
\f0 dev
\f1 \'be\'cd\'b1\'ed\'ca\'be\'b5\'b1\'c7\'b0\'b7\'d6\'d6\'a7\'d4\'da
\f0 dev
\f1 \'c9\'cf
\f0 \
		
\f1 \'b4\'cb\'ca\'b1\'b8\'c4\'b1\'e4\'b5\'c4\'ca\'b1
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'a3\'ac
\f0 master
\f1 \'b7\'d6\'d6\'a7\'ce\'de\'b1\'e4\'bb\'af\'a3\'ac\'cd\'ea\'b3\'c9\'d0\'de\'b8\'c4\'ba\'f3\'b0\'d1
\f0 dev
\f1 \'ba\'cf\'b2\'a2\'b5\'bd
\f0 master
\f1 \'c9\'cf\'bc\'b4\'bf\'c9\'a3\'ac\'d7\'ee\'bc\'f2\'b5\'a5\'b7\'bd\'ca\'bd\'ca\'c7\'a3\'ba
\f0 \
		
\f1 \'d6\'b1\'bd\'d3\'b0\'d1
\f0 master
\f1 \'d6\'b8\'cf\'f2
\f0 dev
\f1 \'b5\'c4\'b5\'b1\'c7\'b0\'cc\'e1\'bd\'bb\'a1\'a3
\f0 \
		
\f1 \'ba\'cf\'b2\'a2\'cd\'ea\'b3\'c9\'ba\'f3\'a3\'ac\'d6\'b1\'bd\'d3\'c9\'be\'b3\'fd
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'be\'cd\'b0\'d1
\f0 dev
\f1 \'d6\'b8\'d5\'eb\'c9\'be\'b5\'f4\'c1\'cb\'a3\'ac\'d6\'bb\'c1\'f4\'d6\'f7\'b7\'d6\'d6\'a7
\f0 master\
		1----
\f1 \'b4\'b4\'bd\'a8
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'b2\'a2\'c7\'d0\'bb\'bb\'b5\'bd
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'a3\'ba
\f0 git checkout -b dev(git branch dev    git checkout dev)\
		2----git branch
\f1 \'b2\'e9\'bf\'b4\'b5\'b1\'c7\'b0\'b7\'d6\'d6\'a7\'a3\'ba
\f0 git branch
\f1 \'a3\'a8\'b5\'b1\'c7\'b0\'b7\'d6\'d6\'a7\'c7\'b0
\f0 *
\f1 \'a3\'a9
\f0 \
		3----
\f1 \'b5\'b1\'c7\'b0\'b7\'d6\'d6\'a7\'b2\'d9\'d7\'f7\'a3\'ba
\f0 git add readme.txt   git commit -m "branch dev change"\
		4----dev
\f1 \'b9\'a4\'d7\'f7\'cd\'ea\'b3\'c9\'a3\'ac\'c7\'d0\'bb\'bb\'bb\'d8
\f0 master
\f1 \'b7\'d6\'d6\'a7\'a3\'ba
\f0 git checkout master\
		5----
\f1 \'b0\'d1
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'c4\'da\'c8\'dd\'ba\'cf\'b2\'a2\'b5\'bd
\f0 master
\f1 \'a3\'ba
\f0 git merge dev\
		6----
\f1 \'ba\'cf\'b2\'a2\'cd\'ea\'b3\'c9\'a3\'ac\'c9\'be\'b3\'fd
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'a3\'ba
\f0 git branch -d dev\
		7----
\f1 \'b2\'e9\'bf\'b4\'b5\'b1\'c7\'b0\'b7\'d6\'d6\'a7\'a3\'ba
\f0 git branch
\f1 \'a3\'a8\'d6\'bb\'ca\'a3\'cf\'c2
\f0 master
\f1 \'b7\'d6\'d6\'a7\'c1\'cb\'a3\'a9
\f0 \
		\
		
\f1 \'d7\'a2\'a3\'ba\'b2\'e9\'bf\'b4\'d0\'de\'b8\'c4\'ce\'c4\'bc\'fe\'c4\'da\'c8\'dd\'a3\'ba
\f0 vi filename
\f1 \'a3\'ac\'c8\'e7\'b9\'fb\'b3\'e5\'cd\'bb\'c1\'cb\'a3\'ac\'d4\'da\'ce\'c4\'bc\'fe\'d6\'d0\'ba\'cf\'b2\'a2\'c4\'da\'c8\'dd\'d6\'d8\'d0\'c2\'c9\'cf\'b4\'ab\'bc\'b4\'bf\'c9
\f0 \
			git log --graph
\f1 \'c3\'fc\'c1\'ee\'bf\'c9\'d2\'d4\'bf\'b4\'b5\'bd\'b7\'d6\'d6\'a7\'ba\'cf\'b2\'a2\'cd\'bc\'a3\'a8
\f0 git log --graph --pretty=oneline --abbrev-commit
\f1 \'a3\'a9
\f0 \
			\
			\
	
\f1 \'b7\'d6\'d6\'a7\'b9\'dc\'c0\'ed\'b2\'df\'c2\'d4
\f0 \
		Fast Forward
\f1 \'c4\'a3\'ca\'bd\'cf\'c2\'c9\'be\'b3\'fd\'b7\'d6\'d6\'a7\'be\'cd\'b6\'aa\'b5\'f4\'b7\'d6\'d6\'a7\'d0\'c5\'cf\'a2\'a3\'ac\'ce\'d2\'c3\'c7\'ca\'b5\'d5\'bd
\f0 --no-ff
\f1 \'b7\'bd\'ca\'bd\'b5\'c4
\f0 git merge\
			1--- git checkout -b dev\
			2--- git add readme.txt\
			3--- git commit -m "
\f1 \'d7\'a2\'bd\'e2
\f0 "\
			4--- git checkout master \
			5--- git merge --no-ff -m "merge with no-ff" dev\
			6--- git log --graph --pretty=oneline --abbrev-commit
\f1 \'ba\'cf\'b2\'a2\'ba\'f3\'b2\'e9\'bf\'b4\'b7\'d6\'d6\'a7\'c0\'fa\'ca\'b7
\f0 \
			\
		
\f1 \'ba\'cf\'b2\'a2\'b7\'d6\'d6\'a7\'ca\'b1\'a3\'ac\'bc\'d3\'c9\'cf
\f0 --no-ff
\f1 \'b2\'ce\'ca\'fd\'be\'cd\'bf\'c9\'d2\'d4\'d3\'c3\'c6\'d5\'cd\'a8\'c4\'a3\'ca\'bd\'ba\'cf\'b2\'a2\'a3\'ac\'ba\'cf\'b2\'a2\'ba\'f3\'b5\'c4\'c0\'fa\'ca\'b7\'d3\'d0\'b7\'d6\'d6\'a7\'a3\'ac
\f0 \
		
\f1 \'c4\'dc\'bf\'b4\'b3\'f6\'c0\'b4\'d4\'f8\'be\'ad\'d7\'f6\'b9\'fd\'ba\'cf\'b2\'a2\'a3\'ac\'b6\'f8
\f0 fast forward
\f1 \'ba\'cf\'b2\'a2\'be\'cd\'bf\'b4\'b2\'bb\'b3\'f6\'c0\'b4\'d4\'f8\'be\'ad\'d7\'f6\'b9\'fd\'ba\'cf\'b2\'a2
\f0 	\
			7--- git stash	
\f1 \'b5\'b1\'c7\'b0\'b9\'a4\'d7\'f7\'cf\'d6\'b3\'a1
\f0 \'93
\f1 \'b4\'a2\'b2\'d8
\f0 \'94
\f1 \'c6\'f0\'c0\'b4\'a3\'ac\'b5\'c8\'d2\'d4\'ba\'f3\'bb\'d6\'b8\'b4\'cf\'d6\'b3\'a1\'ba\'f3\'bc\'cc\'d0\'f8\'b9\'a4\'d7\'f7
\f0 \
			8--- 
\f1 \'c8\'b7\'b6\'a8\'d4\'da\'c4\'c4\'b8\'f6\'b7\'d6\'d6\'a7\'c9\'cf\'d0\'de\'b8\'b4
\f0 bug  git checkout -b issue-101	\
			9--- 
\f1 \'d0\'de\'b8\'b4
\f0 bug
\f1 \'a3\'ac\'c9\'cf\'b4\'ab
\f0  git add name  git commit -m "fixed"\
			10--- git checkout master 	\
			11--- git merge --no-ff -m "merged bug fix 101" issue-101    \
				  git branch -d issue-101\
				  git checkout dev
\f1 \'bb\'d8
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'bc\'cc\'d0\'f8\'b9\'a4\'d7\'f7
\f0 \
			12--- git status 
\f1 \'b9\'a4\'d7\'f7\'c7\'f8\'ca\'b1\'b8\'c9\'be\'bb\'b5\'c4
\f0 \
			      git stash list 
\f1 \'b9\'a4\'d7\'f7\'c7\'f8\'d4\'da\'a3\'ac\'b5\'ab\'d0\'e8\'d2\'aa\'bb\'d6\'b8\'b4
\f0 \
					  
\f1 \'d2\'bb\'a3\'ba
\f0 git stash apply  
\f1 \'c8\'bb\'ba\'f3
\f0  git stash drop 
\f1 \'c0\'b4\'c9\'be\'b3\'fd
\f0 stash
\f1 \'c4\'da\'c8\'dd
\f0 \
					  
\f1 \'b6\'fe\'a3\'ba
\f0 git stash pop 
\f1 \'bb\'d6\'b8\'b4\'cd\'ac\'ca\'b1\'c9\'be\'b3\'fd
\f0 \
				  git stash list
\f1 \'b2\'e9\'bf\'b4\'a3\'ac\'be\'cd\'bf\'b4\'b2\'bb\'b5\'bd\'c8\'ce\'ba\'ce
\f0 stash
\f1 \'c4\'da\'c8\'dd\'c1\'cb
\f0 \
            13--- 
\f1 \'d2\'aa\'b6\'aa\'c6\'fa\'d2\'bb\'b8\'f6\'c3\'bb\'d3\'d0\'b1\'bb\'ba\'cf\'b2\'a2\'b9\'fd\'b5\'c4\'b7\'d6\'d6\'a7\'a3\'ac
\f0 git branch -D feature-vulcan \
			\
			master
\f1 \'b7\'d6\'d6\'a7\'ca\'c7\'d6\'f7\'b7\'d6\'d6\'a7\'a3\'ac\'d2\'f2\'b4\'cb\'d2\'aa\'ca\'b1\'bf\'cc\'d3\'eb\'d4\'b6\'b3\'cc\'cd\'ac\'b2\'bd\'a3\'bb
\f0 \
			$ git push origin master\
			\
			dev
\f1 \'b7\'d6\'d6\'a7\'ca\'c7\'bf\'aa\'b7\'a2\'b7\'d6\'d6\'a7\'a3\'ac\'cd\'c5\'b6\'d3\'cb\'f9\'d3\'d0\'b3\'c9\'d4\'b1\'b6\'bc\'d0\'e8\'d2\'aa\'d4\'da\'c9\'cf\'c3\'e6\'b9\'a4\'d7\'f7\'a3\'ac\'cb\'f9\'d2\'d4\'d2\'b2\'d0\'e8\'d2\'aa\'d3\'eb\'d4\'b6\'b3\'cc\'cd\'ac\'b2\'bd\'a3\'bb
\f0 \
			
\f1 \'c8\'e7\'b9\'fb\'d2\'aa\'cd\'c6\'cb\'cd\'c6\'e4\'cb\'fb\'b7\'d6\'d6\'a7\'a3\'ac\'b1\'c8\'c8\'e7
\f0 dev
\f1 \'a3\'ac\'be\'cd\'b8\'c4\'b3\'c9\'a3\'ba
\f0 \
			$ git push origin dev\
		\
		git status\
		git add hello.txt\
		git commit -m "one change"\
		git push origin dev\
		
\f1 \'b3\'e5\'cd\'bb\'a3\'ba
\f0 \
		git pull\
		
\f1 \'c8\'d4\'d3\'d0\'ce\'ca\'cc\'e2
\f0 ,
\f1 \'c3\'bb\'d3\'d0\'d6\'b8\'b6\'a8\'b1\'be\'b5\'d8
\f0 dev
\f1 \'b7\'d6\'d6\'a7\'d3\'eb\'d4\'b6\'b3\'cc
\f0 origin/dev
\f1 \'b7\'d6\'d6\'a7\'b5\'c4\'c1\'b4\'bd\'d3
\f0 .
\f1 \'bd\'a8\'c1\'a2\'b1\'be\'b5\'d8\'b7\'d6\'d6\'a7\'ba\'cd\'d4\'b6\'b3\'cc\'b7\'d6\'d6\'a7\'b5\'c4\'b9\'d8\'c1\'aa
\f0 :\
		git branch --set-upstream dev origin/dev\
		git pull\
		
\f1 \'ca\'d6\'b6\'af\'d0\'de\'b8\'c4\'b3\'e5\'cd\'bb\'a3\'ac\'cc\'e1\'bd\'bb\'bc\'b4\'bf\'c9
\f0 add commit  git push origin dev\
	\
	
\f1 \'b1\'ea\'c7\'a9\'b9\'dc\'c0\'ed
\f0 \
		
\f1 \'b7\'a2\'b2\'bc\'d2\'bb\'b8\'f6\'b0\'e6\'b1\'be\'ca\'b1\'a3\'ac\'ce\'d2\'c3\'c7\'cd\'a8\'b3\'a3\'cf\'c8\'d4\'da\'b0\'e6\'b1\'be\'bf\'e2\'d6\'d0\'b4\'f2\'d2\'bb\'b8\'f6\'b1\'ea\'c7\'a9\'a3\'a8
\f0 tag
\f1 \'a3\'a9
\f0 \
		tag
\f1 \'be\'cd\'ca\'c7\'d2\'bb\'b8\'f6\'c8\'c3\'c8\'cb\'c8\'dd\'d2\'d7\'bc\'c7\'d7\'a1\'b5\'c4\'d3\'d0\'d2\'e2\'d2\'e5\'b5\'c4\'c3\'fb\'d7\'d6\'a3\'ac\'cb\'fc\'b8\'fa\'c4\'b3\'b8\'f6
\f0 commit
\f1 \'b0\'f3\'d4\'da\'d2\'bb\'c6\'f0\'a1\'a3
\f0 \
		git branch \
		git checkout master\
		git tag v1.0 
\f1 \'bc\'b4\'bf\'c9\'b4\'f2\'c9\'cf\'d2\'bb\'b8\'f6\'d0\'c2\'b1\'ea\'c7\'a9
\f0 \
		git tag
\f1 \'b2\'e9\'bf\'b4\'cb\'f9\'d3\'d0\'b1\'ea\'c7\'a9
\f0 \
		
\f1 \'d5\'d2\'b5\'bd\'c0\'fa\'ca\'b7\'cc\'e1\'bd\'bb\'b5\'c4
\f0 commit id
\f1 \'a3\'ac\'be\'cd\'bf\'c9\'d2\'d4\'b4\'f2\'c9\'cf\'c1\'cb
\f0 \
		git log --pretty=oneline --addrev-commit\
		
\f1 \'b6\'d4\'d3\'a6
\f0 commit id
\f1 \'a3\'ba
\f0 \
		git tag v0.9 6224937\
		
\f1 \'b1\'ea\'c7\'a9\'b2\'bb\'ca\'c7\'b0\'b4\'ca\'b1\'bc\'e4\'cb\'b3\'d0\'f2\'c1\'d0\'b3\'f6\'a3\'ac\'b6\'f8\'ca\'c7\'b0\'b4\'d7\'d6\'c4\'b8\'c5\'c5\'d0\'f2\'b5\'c4
\f0 \
		git show v0.9\
		
\f1 \'bb\'b9\'bf\'c9\'d2\'d4\'b4\'b4\'bd\'a8\'b4\'f8\'d3\'d0\'cb\'b5\'c3\'f7\'b5\'c4\'b1\'ea\'c7\'a9\'a3\'ac\'d3\'c3
\f0 -a
\f1 \'d6\'b8\'b6\'a8\'b1\'ea\'c7\'a9\'c3\'fb\'a3\'ac
\f0 -m
\f1 \'d6\'b8\'b6\'a8\'cb\'b5\'c3\'f7\'ce\'c4\'d7\'d6\'a3\'ba
\f0 \
		$ git tag -a v0.1 -m "version 0.1 released" 3628164\
		
\f1 \'c9\'be\'b3\'fd\'a3\'ba
\f0 \
		$ git tag -d v0.1\
		
\f1 \'cd\'c6\'cb\'cd\'c4\'b3\'b8\'f6\'b1\'ea\'c7\'a9\'b5\'bd\'d4\'b6\'b3\'cc
\f0 \
		$ git push origin v1.0\
		
\f1 \'d2\'bb\'b4\'ce\'d0\'d4\'cd\'c6\'cb\'cd\'c8\'ab\'b2\'bf\'c9\'d0\'ce\'b4\'cd\'c6\'cb\'cd\'b5\'bd\'d4\'b6\'b3\'cc\'b5\'c4\'b1\'be\'b5\'d8\'b1\'ea\'c7\'a9\'a3\'ba
\f0 \
		git push origin --tags\
		
\f1 \'cf\'c8\'b4\'d3\'b1\'be\'b5\'d8\'c9\'be\'b3\'fd\'a3\'ba
\f0 \
		$ git tag -d v0.9\
		
\f1 \'b4\'d3\'d4\'b6\'b3\'cc\'c9\'be\'b3\'fd
\f0 :\
		$ git push origin :refs/tags/v0.9\
\
\
}
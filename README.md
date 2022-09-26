# **오픈소스SW개발론**

### Introduction

-------------
### Week1-1 강의 개요 (강의계획서)
* [Professor's github Repo](https://github.com/kwanghoon)


-------------
### Week1-2 오픈소스소프트웨어 개요

#### 🤷 What is Open Source Software❓
- Software whose copyright holder gives the right to publish, use, copy, modify, and distribute the source code to everyone.

#### 📑 OSS License
- The scope of use, reproduction, modification, and distribution rights of the open source software.

#### 🥊 Free Software vs. Open Source Software
- Free Software is **_not_** for sale free(공짜아님).  

  Examples of OSS Licenses

  | Licenses | Linking with Proprietary SW | Must publish Modification | Patent Protection |
  | --- | --- | --- | --- |
  | GPL 2.0 | NO | Yes | No |
  | LGPL | Yes | Yes | No |
  | MIT, BSD | Yes | No | No |
  | Apache 2.0, MPL 1.0/1.1 | Yes | Yes | Yes |


-------------
### Week2-1 버전 관리 개요
#### 🌳 Version Control System ( VCS )
- Track your files over time so that you can easily get back to a previous working version.
- VCS software
  - CVS ( Concurrent Version System )
  - SVN ( Subversion )
  - Mercurial
  - Darcs
  - Git
- Repository or Repo (저장소)
- General Actions in VCS
  - Checkin
  - Checkoust
  - Diffs
  - Branchig
  - Merging
  - Conflics -> How to resolve❓
  - Tagging  

#### 🧰 Two Main Types of VCS
- ☝️Centralized VCS
  > One central repository with many users.  
  >>   E.g., CVS, SVN, Darcs

- ☁️ Decentralized (Distributed) VCS
  > Every user owns his or her local repository.  
  > A seperate remote (central) repository.  
  > ➕ Two new actions (with remote repositories): `fork` & `pull request`  
  >>   E.g., GIT, Mercurial

#### 🌴 Git
- Linus Tovalds
  - For collaboration of development of Linux kernel
- History 관리하는 tool.
- A distributed version control system
  - Workspace : files you are working with. ( must imply `.git` hidden file )
  - Index : files to be considered in the next commit.
  - Local repository
  - Remote repository 

-------------
### Week2-2 Git
#### 🗣️ Commands of Git
- `# cd <dirname>`, `# mkdir <dirname>`
- `# git init`
- `# git add <file name>`
- `# git reset`
- `# git config -- global user.name "username"`
- `# git config -- global user.email "useremail"`
- `# git commit -am "commit message"`
- `# git status`, `# git diff`, `git log`, `# git shortlog`,`# git show` -> 상태확인
- `# git remote add origin <remote repo_path>`
- `# git pull`
- `# git push origin master`

<img src='https://business-science.github.io/shiny-production-with-aws-book/img/09_git_cli/git_commands.png' width=500>

-------------
### Week2-3 Github, fork, pull request
* Pull-request 의미❓
  * 다른 프로젝트에 내가 만든 commit을 제출한다.
* 상대박 프로젝트를 fork(copy) -> 내 계정에서 관리되느 프로젝트로 새롭게 저장 -> 이를 토대로 commit 내용들으 pull-request 제출 가능.
> ** fork는 본인 프로젝트를 대상으로 하느 것 ✖️ **

#### 🗣️ Commands of Git
- `# git clone <repo_path>`
- `# git checkout -b develop`
- `# git branch`
- `# git remote add upstream <someoneelse's repo_path>`
- `# git fetch upstream <branch name>`
- `# git rebase upstream/<branch name>`
- `# git blame <file name>`


[My Github Blog](https://github.com/Yeonsoo-Sim)

-------------
### Week3     Markdown    
#### What is Markdown❓
> A lightweight markup language for creating formatted text using a plain-text editor

#### You can use
* **bold**
* *italic*
* **_both bold and italic_**
* * list
* > blockquote
* `code`
* ```long long long  code ```
* math $a^2 + b^2 = c^2$  
* - [X] checked box
* - [ ] unchecked box
* ![image] ('image_url')

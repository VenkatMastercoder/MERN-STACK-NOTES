# GIT & GITHUB



# INSTALL GIT 
- [﻿git-scm.com/downloads](https://git-scm.com/downloads) 

---

# FIRST TIME WHEN YOU INSTALL GIT


- COPY THIS COMMANDS BY REPLACING NAME AND EMAIL ID
```
  git config --global user.name "Your Name"
```
```
  git config --global user.email "youremail@example.com"
```
- **BY USING THIS BOTH COMMANDS WHICH WILL HELP YOU TO SET YOU NAME AND MAIL ID TO GIT**
---

# LOCAL TO REMOTE


**THERE ARE FIVE STEP IN THIS PROCESS OF SEND THE FILES FROM LOCAL TO REMOTE REPO**

**STEP 1 : CREATE LOCAL REPOSITORY**

```
git init
```
NOTE : LOCAL REPOSITORY NAME [ **master --> Default Name or Branch for Local Repository** ]

**STEP 2 : Add all file in directory to staging area** 

```
git add .
```
**STEP 3 : SAVE YOUR FILE TO LOCAL REPOSITORY**

```
git commit -m "commit message"
```
**STEP 4 : Now make the Connection Between Local Repository & Remote Repository**

```
git remote add origin URL_LINK
```
**STEP 5 : Now Send Your Code to Remote Repository**

```
git push -u origin master
```
- **Local Repository Name : master**
- **Remote Repository Name : origin**
- -u --> will set connection to Local [master] to Remote [origin] for first time To tell the git 
---

#### **CHECKING COMMANDS IN GIT**
- This Command Help to Check the File Are Saved To Local Repository 
```
git log 
```
- This Command Help to Check the File Are Send To Staging Area
```
git status
```
- This Command Help to Check the Connection B/w Remote Repository To Local Repository
```
git remote -v
```



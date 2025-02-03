# How to use git
### Setting
```cmd
git config --global user.name "Your Name"       # Set User
git config --global user.email "your@email.com" # Set Email
git config --list                               # check all settings
```
### If you want set this only repository
```cmd
git config user.name "Your Name"
git config user.email "your_email@example.com"
```
### start project use :
```cmd
git init
```
### add remote repository use :
```cmd
git remote add origin <repo_url>
```
### check remote use :
```cmd
git remote -v
```
### remove remote repository
```cmd
git remote remove origin
```
### clone repository use :
```cmd
git clone <repo_url>
git clone -b <branch_name> --single-branch <repo_url>
git branch -a # Check branch in repo that clone
```
### check status file
```cmd
git status 
```
### add file into staging area
```cmd
git add <name_file>
git add .
```
### commit file save your progress
```cmd
git commit -m "your_message"
git commit -am "Your message"
```
### file into repository
```cmd
git push origin <current_branch>
```
### pull file from branch or main
```cmd
git pull origin <current_branch>
```
### backward
```cmd
git checkout -- <file>     # cancel change
git reset HEAD <file>      # out to Staging Area
git reset HEAD .           # out all file to Staging Area
git reset --soft HEAD      # delete commit latest (store code)
git reset --hard HEAD      # delete commit latest (delete all code)
```
### manage branch
```cmd
git fetch                    # pull info repo
git branch                   # list branch
git branch <branch-name>     # create new branch 
git checkout <branch-name>   # switch other branch 
git checkout -b <branch>     # create new branch and switch now
git merge <branch-name>      # sum branch into current branch
git branch -d <branch-name>  # delete branch
```
### check history and compare
```cmd
git log                   # check history commit
git log --oneline --graph # check a brief, structured history
git diff                  # See the differences between changed files
```
### Untrack Git For Window
```cmd
rmdir /s /q .git
dir /a             # Check
```

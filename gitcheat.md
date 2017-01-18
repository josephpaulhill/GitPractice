#Git Cheatsheet
**Name:** Joseph Paul Hill  
**Date:** January 17, 2017  
  
Set up account:
- `git config --global user.name "[name]"`
- `git config --gobal user.email [emal address]`
- `git config --list`  
  
Monitor a new repository:
- `git init`
- `git remote add origin [URL of your remote repo]`
- `git remote -v`
  
Add and update files:
- `git status`
- `git add [file name or . to stage all files in repository]`
- `git commit -m "[clear message describing the changes you made]"`
- `git reset`
- `git push origin master`
  
Copy someone else's repository:
- `git clone [URL code]`
  
Check history of repository:
- `git log`
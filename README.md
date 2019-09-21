# DSC first Session - Git

First session for DSC was how to use git.
This is the commands that i've reviewed

### Basic


* Initialize git
```
- git init
```
* Add files to log that are gonna be commited
```
- git add [file name]
```
* Commit your files
```
-git commit -m "[message]" // -s : add sign for the code
```
* Check the current status
```
-git status
```
* Check the part of the code that you've changed
```
-git diff
```
* Check the file that you've comitted
```
-git log
```
```
-git shortlog
```
* Connet your remote git repository
```
-git remote add origin [copied URL]
```
* Push yout comitted files
```
-git push origin master
```
* When you want to change commit message -> vi editor would appear
```
-git commit --amend 
```
* You can push with --force or -f if commit ID of the local repository is not matched with the git repository. at this moment, you maybe need to pull the git repository first
```
-git push origin master --force
```
* If you want to cancel file you've added
```
-git reset 
```
* Remove the very latest file you've commited
```
-git reset HEAD~1 
```
* Make a new branch
```
-git checkout -b develop
```
* Clone the git repository
```
-git clone [git URL]
```
* Check which branch are you in 
```
-git branch
```
* Merge other branch with that branch you are in now
```
git merge [name of the other branch]
```

### Advanced
* Rebase

```
git remote add upstream [forked one's URL(not my repository)]
```
* Get dev branch
```
git fetch upstream dev
```
* Check current branch
```
git status
```
* Rebase
```
git rebase upstream/dev
```

* Modify commit that are placed in the middle of other commits
```
git rebase -i --root
```
* Once vi editor has opened, remove pick and write edit, save it and escape vi editor
```
git status
```
* modify information of commit, and end with --continue
```
git commit --amend -sm "[message]"
```
git rebase --continue
```





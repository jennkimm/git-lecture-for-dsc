# DSC first Session - Git

First session for DSC was how to use git.
```
- git init
```
<add files to log that are gonna be commited>
```
- git add [file name]
```
-
```
-git commit -m "[message]" // -s : add sign for the code
```
-
```
-git status
```
<check the part of the code that you've changed>
```
-git diff
```
<check the file that you've comitted>
```
-git log
```
```
-git shortlog
```

```
-git remote add origin [copied URL]
```
```
-git push origin master
```
<when you want to change commit message -> vi editor would appear>
```
-git commit --amend 
```
<you can push with --force or -f if commit ID of the local repository is not matched with the git repository>
<at this moment, you maybe need to pull the git repository first> 
```
-git push origin master --force
```
<if you want to cancel file you've added
```
-git reset 
```
<remove the very latest file you've commited>
```
-git reset HEAD~1 
```
<make a new branch>
```
-git checkout -b develop
```
<clone the git repository>
```
-git clone [git URL]
```
<check which branch are you in>
```
-git branch
```
<merch other branch with that branch you are in now>
```
git merge [name of the other branch]
```


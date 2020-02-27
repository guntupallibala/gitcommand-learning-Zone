## How to delete files in git?
## ans: we can delete files in two ways.

## way1:
```
step1: delete file in working area
step2: add file to staging area, for that use command "git add ."
step3: changes commit to local repository, for use :  " git commit -m "commit message"
step4: git push origin branch-name   
```

## way2: 
```
step1: git rm file-name
step2: git commit -m "commit message" 
Note: In the case of "git rm " command ,., it will delete file in work area and automatically add to staging area"
step3: git push origin master
``` 
# CMDs
useful cmds

remove all merged branch from local repo
```
git branch --merged | grep -v "\*" | grep -v master | xargs -n 1 git branch -d
```

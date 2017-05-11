# CMDs
useful cmds

## git

- remove all merged branch from local repo
```
git branch --merged | grep -v "\*" | grep -v master | xargs -n 1 git branch -d
```

autocorrect git
```
git config --global help.autocorrect 1
```

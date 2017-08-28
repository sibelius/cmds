# CMDs
useful cmds

## git

- remove all merged branch from local repo
```
git branch --merged | grep -v "\*" | grep -v master | xargs -n 1 git branch -d
```

- autocorrect git
```
git config --global help.autocorrect 1
```

- remove all untracked files and folders
```
git clean -fd
```

## react native

remove all accidentally added .babelrc files present in node_modules
```
find node_modules/ -type f -name .babelrc | grep -v packager | xargs rm
```

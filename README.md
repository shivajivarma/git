# git


## Configure mergetool
```bash
git config --global --add merge.tool kdiff3  
git config --global --add mergetool.kdiff3.path "C:/Program Files/KDiff3/kdiff3.exe"  
git config --global --add mergetool.kdiff3.trustExitCode false

git config --global --add diff.guitool kdiff3  
git config --global --add difftool.kdiff3.path "C:/Program Files/KDiff3/kdiff3.exe"  
git config --global --add difftool.kdiff3.trustExitCode false
```


## Remember password for git
### Ubuntu
```bash
git config --global credential.helper cache
```

### Windows
```bash
git config --global credential.helper wincred
```

## Revert local commit without lossing changes
```bash
git reset --soft HEAD~1
```

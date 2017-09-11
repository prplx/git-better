# git-better
## Collection of git tips

### Delete local and remote branch
```
git branch -d <branch>
git push origin :<branch>
```

### Show all remote merged branches
```
git branch -a --merged
```

### Cherry pick only changes to certain files
```
git cherry-pick -n <commit>
git reset HEAD
git add <path>
git checkout .
git clean -f

```

# git-better
## Collection of git tips

### Rename branch locally and remotely
```
git branch -m <old_branch> <new_branch>
git push origin :<old_branch>
git push --set-upstream origin <new_branch>
```

### Delete branch locally and remotely
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

### Checkout previous branch
```
git checkout -
```

### Remove a file from history
```
git filter-branch --index-filter 'git rm -rf --cached --ignore-unmatch path_to_file' HEAD
```

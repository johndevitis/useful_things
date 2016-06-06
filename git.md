# log

pretty commit view
```
git log --oneline --decorate
```

graph version
```
git log --oneline --decorate --graph --all
```

# untracked files
commit all changes first - they **will** be removed
```
git rm -r --cached .
git add .
git commit -m "fixed untracked files"
```

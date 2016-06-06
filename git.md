# pretty commit view
```
git log --oneline --decorate
```

# graph version
```
git log --oneline --decorate --graph --all
```

# if .gitignore file updated but files still tracked
# COMMIT CHANGES FIRST, they will be removed
```
git rm -r --cached .
git add .
git commit -m "fixed untracked files"
```

Collection of most frequently used git commands
======
Git basics - Pushing files to Remote
```javascript
git add .
git  commit -m 'Message'
git push origin master
```
Git reset local changes
```javascript
git reset --hard HEAD
git clean -f -x -d -n
```
Check existing remote URL
```javascript
git remote -v
```


Git add remote URL
```javascript
git remote add origin git@github.com:username/repo.git
```

Git change remote URL
```javascript
git remote set-url origin git@github.com:username/repo.git
```

Reset git add. before commit
```javascript
git reset
```

Sync a fork
Add Upstream
```javascript
git remote add upstream git@github.com:username/repo.git // main form url
git fetch upstream  // fetch upstream to local
git merge upstream/master  //merge to master
git push origin master
```

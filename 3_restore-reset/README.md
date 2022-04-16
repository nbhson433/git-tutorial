# Git Reset

## Git restore
```html
"git restore --staged "tên file"
``` 
Loại bỏ file change ra khỏi state


## git reset
```html
git reset .
``` 
Loại bỏ file change ra khỏi state
```html
git reset "tên file"
``` 
Dùng để unstate file
```html
git reset "commitId"
``` 
Dùng để để revert commit (quay về working dir)
```html
git reset --soft "commitId"
``` 
Dùng để để revert commit (quay về staging area)
```html
git reset --mixed "commitId"
``` 
Dùng để để revert commit (quay về working dir)
```html
git reset --hard "commitId"
``` 
Dùng để để revert commit (REMOVE COMMIT + MẤT LUÔN CODE CŨ)
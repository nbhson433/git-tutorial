# Git Merge

## Git branch
```html
git branch
``` 
Xem tất cả những branch hiện tại ở local
```html
git branch "tên branch mới"
``` 
Tạo ra một branch mới
```html
git branch -d "tên branch"
git branch -D "tên branch"
``` 
Xóa một branch ở local
```html
git push origin --delete branch_to_be_deleted
``` 
Xóa một nhánh ở server

-d là viết ngắn gọn của –delete và nó chỉ xóa khi nhánh đó đã được merged vào từ nhánh gốc nó base ra. -D là –delete và –force => xóa hết ko cần quan tâm

## Git fetch
```html
git fetch
``` 
Đồng bộ branch từ server về local

## Git checkout 
```html
git checkout "tên branch"
``` 
Để switch qua lại giữa các branch

## Git amend
```html
git commit --amend -m "new message"
``` 
Gom thành một commit duy nhất

## Git merge
```html
git merge "tên branch"
``` 
Gộp những thay đổi từ 1 branch vào 1 branch

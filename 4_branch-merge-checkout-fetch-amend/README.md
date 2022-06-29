# Git Merge

## Git branch
> git branch
Xem tất cả những branch hiện tại ở local

> git branch "tên branch mới"
Tạo ra một branch mới

> git branch -d "tên branch"
> git branch -D "tên branch"
Xóa một branch ở local

> git push origin --delete "branch in server"
Xóa một nhánh ở server/remote

-d là viết ngắn gọn của –delete và nó chỉ xóa khi nhánh đó đã được merged vào từ nhánh gốc nó base ra. 
-D là –delete và –force => xóa hết ko cần quan tâm

## Git checkout 
> git checkout "tên branch"
Để switch qua lại giữa các branch

> git checkout -b "tên branch"
Tạo nhánh mới và switch sang nhánh mới luôn

## Git fetch
> git fetch
Đồng bộ branch từ server về local

## Git amend
> git commit --amend -m "new message"
Đổi message của commit cuối cùng

## Git merge
> git merge "tên branch"
Gộp những thay đổi từ branch phụ vào branch chính

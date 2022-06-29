# Git là gì?

## Repo (repository)
- Là một dự chứa toàn bộ source code của dự án.
- Repo có 2 loại:
  + `Local repo`: trong máy
  + `Remote repo`: nằm trên máy chủ (có thể pull, push)
- Trong repo thì có rất nhiều commit

## Workflow
- Working directory: thư mục làm việc, nơi xảy ra những thay đổi trong file
- Stating area: Khi `git add` thì những file ở working directory sẽ được add vào stating area này
- Local repo: những thay đổi ở staging area sẽ được đưa vào local repo khi `git commit`
- Remote repo: được dùng để đồng bộ những thay đổi ở local lên remote

## Commit
Mỗi thay thêm sửa xóa code thì sử dụng commit để update repo

Code change (working directory)
-> git add: để đưa code change vào staging area
-> git commit: để đưa code change vào repo local (chỉ những thằng ở trong staging area mới được commit)

# Resolve conflict (xử lí xung đột)

```html

git checkout "nhánh chính"
git pull origin "nhánh chính"

git checkout "nhánh phụ"
git rebase "nhánh chính"
-> fix conflicts
git add .
git commit -m "nội dung"
git rebase --continue
git push orgin -f "nhánh phụ"
``` 


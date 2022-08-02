# Làm chủ github

-   git config --global user.name 'tranacuong102'

-   Tạo ra 1 git repo ở dưới local: git init

-   git status: Kiểm tra trong thư mục dự án có trạng thái ntn

-   git add tên_file : Thêm file theo tên thư mục chuyển sang trạng thái staging area
-   git add . : Thêm toàn bộ file sang trạng thái staging area

-   git log : Xem lại được commit đã tạo

======

# Nâng cao Branch

-   git branch : Kiểm tra các nhánh đang có trong dự án
-   git checkout -b body-style : Tạo ra 1 branch mới
-   git checkout main : Quay trở lại branch main

-   git restore --staged style2.css => Đưa thư mục lại trạng thái đang làm việc

-   git merge body-style => Đưa các commit từ body-style vào branch main

-   git checkout id_commit: Đưa sourch code về trạng thái trước khi commit

-   git push => Đồng bộ từ local với repo
-   git pull => Đồng bộ từ repo về local

### Xử lý khi trên repo có sự thay đổi mà ở local không biết

-   Trên Repo file index.html thay đổi từ NEW APP
-   Dưới local sửa thành APP NEW

#Sử dụng Github trong dự án

##1. Cài đặt Git

- Tải Git app tại: https://git-scm.com/downloads
- Cài như cài desktop app thông thường
- Tạo 1 tài khoản Github
- Cấu hình git:
  * Vào Git bash > gõ lệnh : git config --list
    - Set your username:
git config --global user.name "FIRST_NAME LAST_NAME"

    - Set your email address:
git config --global user.email "MY_NAME@example.com"

##2. Tạo Project
- Clone 1 project có sẵn: Vào thư mục muốn lưu code trên máy > Mở git bash > lệnh => git clone [link code github] > done
- Tạo project trên github.
  * Tạo 1 github repository (folder) - nơi chưa code trên github
  * Clone project này về máy (git clone link)
  * Code:
    [git status] - kiểm tra trạng thái file
    [git ad .] - thêm file
    [git commit -m "[message]"] - tạo nội dung commit
    [git push origin main] - đẩy code lên
- Tạo project trên local và đẩy lên github
  * Tạo 1 github repository (folder)
  * [git init]
  * Code: 
    [git status]
    [git add .]
    [git commit -m "[message]"]
    [git remote add origin https://...]
    [git push origin master]

##3. Https và SSH
Khi dùng Https: Mỗi lần Push github sẽ yêu cầu đăng nhập >> Dùng SSH
- Search : các tạo SSH key - github
- Vào trang docs của github làm theo các bước trong tutorial
- Thử connect máy tính với git [sẽ không bị yêu cầu đăng nhập nữa]

##4. Các câu lệnh thường dùng của Git
- 

##5. Làm việc nhóm với Git

##6. Resolve Conflict
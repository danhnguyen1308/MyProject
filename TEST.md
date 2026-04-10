Hướng dẫn cài Git trên Windows và macOS

## 1. Cài Git trên Windows

1. Truy cập trang chính thức của Git:
   https://git-scm.com/

2. Tải bộ cài cho Windows:
   - Nhấn "Download" để tải file `Git-*-64-bit.exe`.

3. Chạy file cài đặt:
   - Chọn Next để tiếp tục.
   - Giữ các thiết lập mặc định thường là phù hợp.
   - Chọn "Use Git from the Windows Command Prompt" nếu muốn dùng Git trên cả cmd và PowerShell.
   - Giữ các tùy chọn còn lại mặc định và nhấn "Install".

4. Kiểm tra cài đặt:
   - Mở Command Prompt hoặc PowerShell.
   - Chạy:
     git --version
   - Nếu hiển thị phiên bản Git, tức là cài thành công.

## 2. Cài Git trên macOS

### Cách 1: Cài bằng Homebrew

1. Nếu chưa có Homebrew, cài bằng lệnh:
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. Cài Git:
   brew install git

3. Kiểm tra cài đặt:
   git --version

### Cách 2: Cài bằng Xcode Command Line Tools

1. Mở Terminal.
2. Chạy:
   xcode-select --install

3. Chấp nhận cài đặt và đợi hoàn tất.
4. Kiểm tra:
   git --version

## 3. Cấu hình Git ban đầu

1. Thiết lập tên và email:
   git config --global user.name "Ho Ten"
   git config --global user.email "email@example.com"

2. Kiểm tra cấu hình:
   git config --list

## 4. Lưu ý

- Windows: nếu dùng Git Bash, bạn có thể chạy Git trực tiếp trong môi trường Linux-like.
- macOS: nếu đã cài Xcode, Git có thể đã được cài sẵn sẵn.
- Nếu cần cập nhật Git, tải lại bộ cài Windows hoặc dùng `brew upgrade git` trên macOS.

# Git-Safety-Foundation-Before-Vibe-Coding
Dự án thực hành Git/GitHub nền tảng trước khi tham gia Vibe Coding.

## Học viên
- Tên: pham phuoc bao tin
- Trạng thái: Đang thực hành
## Kỹ năng
- Git & Github cơ bản
- Thao tác với command line
- Sử dụng công cụ: Antigravity
- Sử dụng công cụ: VS Code
- Đã hoàn thành khóa học Git/GitHub Foundation

## Quá trình học và thực hành
Trong quá trình thực hiện dự án này, tôi đã hoàn thành các mục tiêu sau:
1. **Khởi tạo và cấu hình:** Tạo repository local và kết nối với GitHub.
2. **Quản lý phiên bản cơ bản:** Thực hiện các thao tác add, commit để lưu lại các mốc thay đổi với 10 commit có ý nghĩa.
3. **Làm việc với Branch:** Tạo và chuyển đổi giữa 3 branch khác nhau (`main`, `tinppb`, `feature-tools`, `final-update`).
4. **Cộng tác qua Pull Request:** Đẩy code lên GitHub và tạo 2 Pull Request để merge tính năng vào nhánh chính.
5. **Xử lý Xung đột (Conflict):** Cố tình tạo ra conflict khi 2 branch cùng sửa một dòng code, sau đó dùng VS Code để phân tích và resolve conflict thành công.
6. **Rollback (Cỗ máy thời gian):** Giả lập tình huống AI sinh code lỗi, commit nhầm và sử dụng lệnh revert để đảo ngược lại thay đổi đó một cách an toàn.

## Danh sách lệnh Git đã sử dụng
- `git init`: Khởi tạo kho lưu trữ.
- `git remote add origin`: Kết nối với kho lưu trữ trên GitHub.
- `git branch -M main`: Đổi tên nhánh chính thành `main`.
- `git checkout -b <branch>`: Tạo và chuyển sang nhánh mới.
- `git checkout <branch>`: Chuyển đổi giữa các nhánh.
- `git add <file>`: Đưa file vào Staging area.
- `git commit -m "<message>"`: Ghi lại thay đổi (tạo snapshot).
- `git push -u origin <branch>`: Đẩy nhánh local lên GitHub.
- `git pull`: Cập nhật code mới nhất từ GitHub về máy.
- `git merge <branch>`: Gộp nhánh.
- `git revert HEAD`: Hoàn tác (đảo ngược) commit bị lỗi gần nhất.
- `git log --oneline`: Xem lịch sử commit rút gọn.

# Đề Thi Thực Hành: Setup Dự Án Front-End Hoàn Chỉnh và Tích Hợp Firebase Authentication

## Mục Tiêu
Thiết lập một dự án frontend hoàn chỉnh với cấu trúc chuẩn, áp dụng các công cụ hỗ trợ code quality, tự động hóa, tài liệu hóa và kết nối xác thực người dùng với Firebase.

## Yêu Cầu Bắt Buộc

### 1. Khởi tạo dự án
- Sử dụng bất kỳ frontend framework (React, Vue, Svelte, Angular, v.v.).
- Tạo cấu trúc thư mục chuẩn: `/assets`, `/components`, `/services`, `/hooks`, `/pages`, `/utils`, `/store`, v.v.

### 2. Cấu hình Git
- Khởi tạo Git repository.
- Thiết lập `.gitignore`, nhánh chính là `main`.
- Viết `README.md` mô tả dự án, cách cài đặt và chạy.

### 3. Cấu hình kiểm tra mã nguồn và formatter
- Cài ESLint, Prettier và thiết lập quy tắc chuẩn.
- Cài Husky + lint-staged để chạy kiểm tra trước khi commit.

### 4. Cấu hình HTTP client
- Tạo wrapper module cho HTTP client (Fetch hoặc Axios).
- Thêm interceptor xử lý token và lỗi.

### 5. Cấu hình quản lý trạng thái
- Dùng bất kỳ state management phù hợp (Redux, Pinia, Zustand, v.v.).
- Tạo store cơ bản và flow xử lý async.

### 6. Cấu hình test
- Cài đặt framework test (Jest, Vitest, RTL, Cypress...).
- Viết ít nhất 1 test cho 1 component và 1 test logic.

### 7. Cấu hình CI đơn giản
- Tạo GitHub Actions workflow:
  - Kiểm tra lint.
  - Chạy test.
  - Build thử.

### 8. Tài liệu component
- Cài đặt Storybook hoặc tương đương.
- Tạo ít nhất 2 stories (component nhỏ và layout).

### 9. Cấu hình biến môi trường
- Sử dụng `.env` cho API base URL, Firebase key, v.v.
- Đảm bảo không đẩy `.env` lên Git.

## Phần Nâng Cao: Kết nối Firebase Authentication

### 10. Tích hợp Firebase
- Đăng ký project Firebase và tạo Web App.
- Kết nối Firebase SDK (phiên bản module).
- Cấu hình Firebase Auth sử dụng Email/Password.

### 11. Tạo UI Login/Signup
- Tạo form login/signup.
- Xử lý logic đăng nhập, đăng ký, đăng xuất bằng Firebase.

### 12. Quản lý Auth State
- Lưu trạng thái đăng nhập qua Context hoặc Store.
- Sử dụng listener (onAuthStateChanged) để đồng bộ trạng thái người dùng.

### 13. Routing bảo vệ
- Thiết lập route bảo vệ (chỉ truy cập nếu đã đăng nhập).
- Redirect về login nếu chưa xác thực.

---

👉 **Gợi ý sử dụng AI:**  
Hãy dùng Cursor AI để:
- Sinh các file config chuẩn (eslint, prettier, husky,...)
- Tạo nhanh component UI, logic auth.
- Sinh các lệnh CI và câu lệnh shell.
- Sinh test cases mẫu cho các phần quan trọng.

🕐 **Thời gian làm bài gợi ý:** 90 phút.

🎯 **Mục tiêu đánh giá:**  
Khả năng setup một dự án có cấu trúc chuẩn, tích hợp xác thực với Firebase, sử dụng AI để tăng tốc workflow phát triển front-end.

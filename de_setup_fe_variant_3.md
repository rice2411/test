# Đề Thi Setup Front-End Cơ Bản – Phiên bản 3

## Mô tả
Đây là đề thi thực hành cho ứng viên Front-End level junior. Yêu cầu setup dự án với các cấu hình kỹ thuật chuẩn.

## Yêu cầu

### 1. Khởi tạo cấu trúc dự án cơ bản
Tạo project base sử dụng framework bất kỳ (React, Vue, Svelte, Angular, ...) với cấu trúc thư mục chuẩn: /assets, /components, /services, /hooks,...

### 2. Cấu hình quản lý version và quy trình Git
Khởi tạo Git repository. Tạo file .gitignore phù hợp. Thiết lập branch chính và mô tả workflow.

### 3. Cấu hình ESlint, Prettier và Format Code
Cài đặt ESLint và Prettier. Thiết lập script trong package.json để lint và format code tự động.

### 4. Cấu hình Lint staged, Husky cho quy trình commit
Cài lint-staged và Husky. Thiết lập hook để kiểm tra lint trước khi commit.

### 5. Tạo tài liệu hướng dẫn và mẫu code tiêu chuẩn cho DEV mới
Tạo README.md mô tả dự án, cách chạy. Viết AI_USAGE.md để mô tả cách dùng Cursor AI hỗ trợ setup.

### 6. Cấu hình CI/CD cho dự án FE
Tạo GitHub Actions để lint, test, build khi push. Có thể dùng template AI đề xuất.

### 7. Tích hợp hệ thống tài liệu tự động (Storybook, Styleguidist)
Cài đặt Storybook và tạo ít nhất 1 story cho component cơ bản.

### 8. Hỗ trợ tạo các file đóng gói hệ thống như: Dockerfile, docker-compose
Viết Dockerfile cho FE app. Optional: Docker Compose nếu có thêm service API giả.

---
👉 Gợi ý: Ứng viên có thể dùng Cursor AI để tạo nhanh file cấu hình, routing, test, API client, UI component,... và ghi rõ trong AI_USAGE.md.

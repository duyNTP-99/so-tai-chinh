# Sổ Tài Chính

Ứng dụng quản lý tài chính cá nhân: sổ thu chi, báo cáo và ngân sách tháng, tài sản ròng, mục tiêu SMART, dự phóng tài chính.

- Cài được lên điện thoại (PWA), dùng được khi không có mạng.
- Dữ liệu lưu trên máy; có thể bật đồng bộ Google Drive trong **Cài đặt**.
- Không có máy chủ riêng: dữ liệu không đi qua đâu ngoài trình duyệt của bạn và Google Drive của bạn.

## Đăng lên GitHub Pages

1. Tạo repository mới trên GitHub (ví dụ `so-tai-chinh`), để **Public**.
2. Đưa toàn bộ nội dung thư mục này lên nhánh `main`.
3. Vào **Settings → Pages**, mục **Build and deployment** chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, bấm **Save**.
4. Sau 1–2 phút, ứng dụng có tại `https://<tên-tài-khoản>.github.io/so-tai-chinh/`.

## Bật đồng bộ Google Drive

Làm theo hướng dẫn trong **Cài đặt → Đồng bộ Google Drive** của ứng dụng. Ở bước tạo OAuth Client ID, mục **Authorized JavaScript origins** điền `https://<tên-tài-khoản>.github.io`.

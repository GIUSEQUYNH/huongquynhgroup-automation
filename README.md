# HUONGQUYNHgroup Automation

Website React/Vite đã cấu hình sẵn để triển khai tự động lên GitHub Pages.

## Địa chỉ dự kiến

`https://TEN-TAI-KHOAN.github.io/huongquynhgroup-automation/`

## Triển khai

1. Tạo repository GitHub tên chính xác `huongquynhgroup-automation`.
2. Tải toàn bộ nội dung dự án lên nhánh `main`.
3. Mở **Settings > Pages**.
4. Tại **Build and deployment > Source**, chọn **GitHub Actions**.
5. Mở **Actions** và chờ workflow hoàn tất.

## Chạy cục bộ

```bash
npm install
npm run dev
```

Nếu đổi tên repository, sửa `base` trong `vite.config.js` cho khớp.

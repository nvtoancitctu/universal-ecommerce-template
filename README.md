# Template chung cho các thiết kế website bán hàng sử dụng framework Laravel.

## Tải về, giải nén và sử dụng.

Có sẵn các thiết kế:
- Trang chủ, các trang hỗ trợ (faq, about_us,...), trang liên hệ
- Cơ sở dữ liệu mẫu: users, auditlogin, systemsetting
```bash
# khởi tạo csdl
php artisan migrate
```
- Chạy dự án chỉ 1 lệnh terminal:
```bash
# không cần mở tab mới chạy thêm: php artisan serve
npm run dev
```
## Cài đặt môi trường phát triển

Để chạy template Laravel, bạn cần cài đặt các phần mềm sau:

1. **XAMPP / LARAGON** – Môi trường localhost (PHP + MySQL):
   - [Tải XAMPP](https://www.apachefriends.org/download.html)  
   - [Tải Laragon](https://laragon.org/download/)

2. **PHP + MySQL** – Nếu muốn cài riêng hoặc cập nhật bản mới nhất:
   - [PHP](https://www.php.net/downloads)  
   - [MySQL](https://dev.mysql.com/downloads/)

3. **Git + GitHub** – Quản lý version code và dự án:
   - [Git](https://git-scm.com/downloads)  
   - [GitHub Desktop](https://desktop.github.com/)

4. **Composer + Node.js** – Quản lý dependencies và build frontend:
   - [Composer](https://getcomposer.org/download/)  
   - [Node.js](https://nodejs.org/en/download/)

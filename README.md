# [Thực hành] Tạo Navbar với Bootstrap

## 🎯 Mục tiêu
Luyện tập sử dụng **Bootstrap Navbar** để tạo thanh điều hướng chuyên nghiệp, hỗ trợ responsive trên cả Desktop, Tablet và Mobile.

---

## 📌 Thông tin học viên / Sinh viên
- **Họ và tên / GitHub:** `dtc245200059-eng`
- **Mã sinh viên:** `DTC245200059`
- **Email:** `dtc245200059@ictu.edu.vn`

---

## 🚀 Các bước thực hiện

### Bước 1: Cài đặt Bootstrap qua CDN
Thêm liên kết Bootstrap CSS trong thẻ `<head>`:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
```
Và nhúng thư viện JavaScript của Bootstrap trước thẻ đóng `</body>`:
```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

### Bước 2: Xây dựng cấu trúc Navbar
- Thẻ `<nav class="navbar navbar-expand-lg navbar-dark bg-dark">`: Thanh điều hướng với giao diện tối (`navbar-dark bg-dark`).
- Thẻ `<a class="navbar-brand" href="#">MyWebsite</a>`: Thương hiệu / Logo website.
- Thẻ `<button class="navbar-toggler" ...>`: Nút mở rộng/thu gọn menu trên giao diện điện thoại.
- Thẻ `<div class="collapse navbar-collapse" id="navbarNav">`: Chứa danh sách các liên kết điều hướng.
- Các mục menu:
  - `Home` (trạng thái `active`)
  - `About`
  - `Services` (dạng `dropdown` chứa *Web Design* và *SEO*)
  - `Contact`

---

## 💻 Cách chạy và kiểm tra kết quả
1. Mở trực tiếp file `index.html` bằng trình duyệt web bất kỳ (Chrome, Edge, Firefox).
2. **Kiểm tra Dropdown:** Bấm vào mục **Services** để kiểm tra menu thả xuống.
3. **Kiểm tra Mobile Responsive:** Bấm phím `F12` trên trình duyệt và chuyển sang chế độ Device Toolbar (Mobile), thanh menu sẽ tự động co lại thành nút 3 gạch (`hamburger button`). Bấm vào nút để xem menu mở ra.

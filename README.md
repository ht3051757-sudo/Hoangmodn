# AURA — Admin Key System + Full Effects + FPS Optimized

Đã thêm khu vực Admin để **thêm/bật/tắt KEY ngay trong web**, không cần sửa file.

### Admin
- Tên hiển thị: `Hoàng [ADMIN]`
- Thêm KEY theo ngày.
- Chọn số lượt sử dụng.
- Bật/tắt KEY.
- Xem số tài khoản.
- Xem số người đang dùng (online activity trong 90 giây gần nhất).
- Xem số tài khoản bị BAN.
- BAN/GỠ BAN tài khoản.

### Demo Admin
Mật khẩu demo hiện nằm trong `app.js` ở biến `ADMIN_PASSWORD`.
**Hãy đổi ngay trước khi public**, vì frontend không thể bảo vệ bí mật thật sự.

### Quan trọng về GitHub Pages
Bản này vẫn lưu dữ liệu bằng `localStorage`, nên Admin thêm KEY trên máy A **không đồng bộ sang máy B**. Chỉ có backend/database mới làm được hệ thống thật với:
- tài khoản server-side,
- Admin role,
- KEY database,
- BAN realtime,
- online presence.

README này cố ý giữ rõ giới hạn để không khiến bản frontend demo bị hiểu nhầm là hệ thống xác thực production.

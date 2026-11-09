# Tin tức update — website bản tin

Website tĩnh, 1 file `index.html` duy nhất, không cần build.

## Deploy lên Vercel qua GitHub
1. Tạo repo GitHub mới `tin-tuc-update`, đẩy toàn bộ thư mục này lên nhánh chính.
2. Trên Vercel: Add New → Project → Import repo `tin-tuc-update` → Deploy (không cần chỉnh gì thêm).
3. Link live sẽ là `https://tin-tuc-update.vercel.app` (hoặc tên Vercel tự đặt).

## Cập nhật hàng ngày (6h / 12h / 20h)
- Sửa `index.html`: thay nội dung bản tin mới nhất, giữ nguyên cấu trúc màu sắc (Trong nước đỏ #C8102E, Quốc tế xanh navy #0B3D91).
- Commit + push lên GitHub → Vercel tự deploy lại trong khoảng 1 phút.
- Bản tin cũ: lưu lại thành `archive/2026-11-06-0600.html` trước khi thay, để trang lưu trữ không mất.

## Bản tin hiện có trong file
- Sáng thứ Sáu 06/11/2026, khung 6h: 3 tin nóng + Top 10 trong nước + Top 10 quốc tế, link bài gốc đầy đủ.

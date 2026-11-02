# Spendlog (PWA)

Ứng dụng ghi chi tiêu, chạy hoàn toàn trên trình duyệt, dữ liệu lưu trong GitHub Gist của bạn.

## Đưa lên GitHub Pages
1. Tạo repo mới, upload toàn bộ nội dung thư mục này (index.html, manifest.webmanifest, sw.js và 4 file icon .png).
2. Settings → Pages → Source: "Deploy from a branch", chọn nhánh `main` và thư mục `/ (root)`.
3. Sau ít phút app chạy tại `https://<tên-bạn>.github.io/<tên-repo>/`.

## Dùng lần đầu
1. Tạo token tại https://github.com/settings/tokens/new?scopes=gist (chỉ cần quyền gist).
2. Mở app → tab Cài đặt → dán token → "Kết nối & tải". Để trống Gist ID thì app tự tạo Gist secret.
3. Thiết bị khác: dán cùng token và Gist ID.

## Cài lên điện thoại
- Android (Chrome): menu ⋮ → "Cài đặt ứng dụng" / "Thêm vào màn hình chính".
- iPhone (Safari): nút Chia sẻ → "Thêm vào Màn hình chính".

## Cập nhật
Sau khi sửa index.html, đổi `VERSION` trong sw.js (v1 → v2) để máy đang cài nhận bản mới.

## Lưu ý bảo mật
Token lưu trong trình duyệt của từng thiết bị. Không ghi token vào code hay commit lên repo.

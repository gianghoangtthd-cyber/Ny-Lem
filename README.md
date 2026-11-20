# nyLem – Website cà phê (bản demo)

Website một tệp `index.html`, không cần cài đặt hay build.

## Đưa lên GitHub Pages
1. Tạo tài khoản tại github.com, bấm **New repository**, đặt tên (ví dụ `nylem`), chọn **Public**, bấm **Create repository**.
2. Bấm **uploading an existing file**, kéo thả `index.html`, `README.md` và `.nojekyll` vào, rồi bấm **Commit changes**.
3. Vào **Settings → Pages**. Ở **Build and deployment**, chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, bấm **Save**.
4. Sau 1–2 phút, trang chạy tại `https://<tên-tài-khoản>.github.io/nylem/`.

## Lưu ý
- Ngoài claude.ai, website chạy ở **chế độ demo**: đơn, tài khoản và điểm chỉ lưu trong trình duyệt của từng người. Quán **không nhận được đơn của khách ở thiết bị khác**.
- Tài khoản demo trong mã nguồn (`admin` / `admin123`, `0900000001` / `demo123`) ai cũng xem được và chỉ có tác dụng trên trình duyệt của chính họ. Không dùng cho dữ liệu thật.
- Muốn nhận đơn thật cho khách bất kỳ, cần thêm backend (ví dụ Supabase hoặc Firebase) với đăng nhập và phân quyền ở phía máy chủ.

1. Vấn đề là gì?
PixelForge dùng lại mật khẩu và lưu trên Chrome, nên nếu máy nhiễm infostealer, nhiều tài khoản có thể bị chiếm cùng lúc
2. Yêu cầu đề bài
Chuyển hơn 40 tài khoản sang Bitwarden, mỗi tài khoản có mật khẩu riêng dài 16–32 ký tự, đồng thời chuẩn bị cách khôi phục khi có sự cố
3. Cách làm
1. Zero-Knowledge: Bitwarden mã hóa két sắt bằng AES-256 trên thiết bị và giải mã tại đó, nên lộ máy chủ không đồng nghĩa lộ mật khẩu
2. Master Passphrase: Dùng ít nhất 6 từ chọn ngẫu nhiên, dài trên 20 ký tự, ví dụ cactus-orbit-lantern-velvet-river-comet — không dùng nguyên mẫu
3. Generator: Đặt 24 ký tự, bật chữ hoa, chữ thường, số và ký tự đặc biệt
4. Chuyển đổi: Đổi mật khẩu 40 tài khoản, lưu vào két sắt rồi xóa bản lưu cũ trên Chrome
5. Chống trang giả: Auto-fill kiểm tra tên miền nên thường không gợi ý mật khẩu thật trên github.com hay steampowered.xyz
6. Khóa cấp cứu: Cấp Trưởng nhóm quyền truy cập két sắt tổ chức và cất mã khôi phục 2FA trong phong bì niêm phong

    

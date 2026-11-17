# Banipu

Nền tảng web ứng dụng AI cá nhân hoá kế hoạch học tập, nuôi dưỡng động lực tự thân cho học sinh THPT dựa trên Thuyết Tự quyết.
Dự thi STEMPETITION 2026–2027 · Tiểu ban Nghiên cứu khoa học · Nhóm Băng, Nghi, Phúc.

## Cấu trúc

| Tệp | Nội dung |
|---|---|
| `index.html` | Trang chủ giới thiệu Banipu |
| `app.html` | Ứng dụng: Tuần này, trò chuyện WOOP với Banipu, check-in hằng ngày, tự đánh giá, tiến bộ, bảng tín hiệu GVCN |
| `assets/` | Thư viện giao diện, hiệu ứng và biểu tượng của trang chủ |
| `favicon.svg`, `share.jpg` | Biểu tượng trang và ảnh chia sẻ |

Website là HTML tĩnh, không cần cài đặt hay build: mở `index.html` bằng trình duyệt, hoặc bật GitHub Pages cho nhánh `main`.

## Lưu ý về bản chạy thử

- Dữ liệu của học sinh lưu trong trình duyệt (localStorage), không gửi đi đâu.
- Số liệu lớp trong bảng GVCN là dữ liệu minh hoạ.
- Ngoài claude.ai, trò chuyện với Banipu chạy theo kịch bản soạn sẵn; AI thật cần thêm một máy chủ trung gian giữ khoá API (xem kế hoạch AI cá nhân hoá).

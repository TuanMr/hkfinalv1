# 🚀 Hộ Kinh Doanh 2026 - AI Consultant

Chào mừng bạn đến với repository của **Hộ Kinh Doanh 2026**, chatbot chuyên gia tư vấn pháp luật và thuế cho Hộ kinh doanh (HKD) và Cá nhân kinh doanh (CNKD) năm 2026.

## 🌟 Giới thiệu
Đây là một AI Assistant được xây dựng trên nền tảng OpenClaw, được thiết kế để giải đáp mọi thắc mắc về thủ tục hành chính, chính sách thuế và quản lý kinh doanh cho các hộ kinh doanh tại Việt Nam, dựa trên các văn bản pháp luật mới nhất (Thông tư 152/2025, Nghị định 68/2026...).

### Đặc điểm nổi bật:
- **Chính xác:** Trả lời dựa trên nguồn dữ liệu chính thống từ Cục Thuế và các văn bản pháp luật.
- **Súc tích:** Ưu tiên câu trả lời ngắn gọn, chia nhỏ vấn đề để người dùng dễ hiểu.
- **Đa kênh:** Hoạt động mượt mà trên cả **Zalo** và **Telegram**.
- **Hỗ trợ trực quan:** Có khả năng cung cấp hình ảnh minh họa cho các thao tác phức tạp (như kê khai eTAX Mobile).

## 🛠️ Cách sử dụng

Bạn có thể tương tác với Bot thông qua hai kênh sau:

### 1. Trên Telegram ✈️
- **Tìm kiếm:** Tìm kiếm username `@hkd2026_bot` hoặc truy cập link bot.
- **Bắt đầu:** Nhấn `/start`.
- **Sử dụng:** Nhắn tin trực tiếp câu hỏi của bạn (Ví dụ: *"Cách đăng ký HKD online?"* hoặc *"Doanh thu 3 tỷ đóng thuế bao nhiêu?"*).

### 2. Trên Zalo 💬
- **Tìm kiếm:** Tìm kiếm Official Account (OA) của **Hộ Kinh Doanh 2026**.
- **Bắt đầu:** Nhắn tin chào hoặc gửi yêu cầu tư vấn.
- **Lưu ý:** Bot hỗ trợ phản hồi tức thì cho mọi người dùng.

## 📚 Cấu trúc dữ liệu trong Repository
- `/knowledge/`: Chứa toàn bộ tri thức cốt lõi.
    - `faq_hkd_2026.md`: 44 câu hỏi thường gặp từ Cục Thuế.
    - `etax_mobile_guide.md`: Hướng dẫn chi tiết kê khai thuế online.
    - `assets_mapping.md`: Ánh xạ hình ảnh minh họa.
- `IDENTITY.md` & `SOUL.md`: Định nghĩa nhân vật, phong cách trả lời và giá trị cốt lõi của Bot.
- `MEMORY_LOG.md`: Hệ thống theo dõi lịch sử tương tác để thấu hiểu người dùng.

## ⚙️ Triển khai (Dành cho Dev)
Project này chạy trên **OpenClaw Gateway**. Để triển khai lại, bạn cần:
1. Cấu hình `botToken` cho Zalo và Telegram trong `openclaw.json`.
2. Import thư mục `/knowledge/` vào workspace của agent.
3. Thiết lập `dmPolicy: "open"` để cho phép người dùng nhắn tin tự do.

---
*Phát triển bởi TuanMr & OpenClaw AI* 🚀

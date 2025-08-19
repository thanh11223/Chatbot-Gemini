📌 Mô tả dự án: Gemini Chatbox với Flask + React + Tailwind
1. Giới thiệu

Dự án xây dựng một ứng dụng chat AI sử dụng Google Gemini API để trả lời tin nhắn người dùng.
Hệ thống được phát triển theo mô hình Frontend - Backend tách biệt:

Backend (Flask): trung gian kết nối giữa client và Gemini API.

Frontend (React + Tailwind): giao diện chat trực quan, hiện đại, nhiều hiệu ứng.

2. Công nghệ sử dụng

Flask (Python): Xây dựng API backend, xử lý request/response.

ReactJS: Hiển thị giao diện chat động trong file chat.html.

TailwindCSS: Tạo giao diện đẹp, responsive, dễ tùy chỉnh màu sắc.

Framer Motion (tùy chọn): Thêm hiệu ứng animation cho bong bóng chat.

Google Gemini API: AI model xử lý ngôn ngữ, trả lời thông minh.

dotenv: Quản lý biến môi trường (API key, cổng chạy).

3. Cấu trúc dự án
📦 gemini_chatbox
 ┣ 📂 templates
 ┃ ┗ 📜 chat.html   → Giao diện React + Tailwind
 ┣ 📜 app.py        → Flask backend
 ┣ 📜 .env          → Lưu API key, config
 ┣ 📜 README.md     → Tài liệu dự án

4. Tính năng chính

✅ Gửi/nhận tin nhắn với AI Gemini.
✅ Giao diện chatbox đẹp, gradient, nhiều hiệu ứng.
✅ Tin nhắn có hiệu ứng hiển thị mượt mà.
✅ Tách biệt frontend và backend, dễ mở rộng.
✅ Tích hợp dễ dàng chỉ với Flask và một file HTML duy nhất.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/681edb6c-4c1f-4ac9-bc39-791731aea1ec" />

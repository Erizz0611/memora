# Ôn Đề Quiz

Biến bộ đề trắc nghiệm thành bài quiz kiểu Quizizz để ôn thi.

- Nhờ AI (ChatGPT, Claude, Gemini…) chuyển file đề sang JSON bằng prompt mẫu có sẵn trong app, rồi dán vào.
- Hai chế độ: **Ôn tập** (chọn xong hiện đúng/sai) và **Kiểm tra** (nộp bài mới chấm).
- Lưu lịch sử làm bài, làm lại câu sai.
- Đăng nhập Google để đồng bộ bộ đề giữa các máy (Firebase Auth + Firestore). Không đăng nhập thì dữ liệu lưu trên trình duyệt.

- Cài lên màn hình chính điện thoại như app thật (biểu tượng riêng, mở toàn màn hình, mở được khi mất mạng):
  - Android (Chrome): menu ⋮ → "Cài đặt ứng dụng" hoặc "Thêm vào màn hình chính".
  - iPhone (Safari): nút Chia sẻ → "Thêm vào MH chính".

Toàn bộ app nằm trong `index.html`, không cần bước build. `manifest.webmanifest`, `sw.js` và thư mục `icons/` dùng cho việc cài lên điện thoại. Trang web: https://erizz0611.github.io/on-de-quiz/

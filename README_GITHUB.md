# ABHIUYEN — Reading & Listening

BỘ WEBSITE TĨNH DÙNG CHO GITHUB PAGES

Cấu trúc:
- index.html — Trang web 16 đoạn song ngữ, luyện nghe và 144 cụm từ.
- mp3/sheet_01.mp3 ... sheet_04.mp3 — 4 bài nghe từng cụm.
- mp3/reading_01.mp3 ... reading_15.mp3 — 15 bản ghi bài đọc không trùng lặp.

Lưu ý: Bản ghi 9_49PM(1).wav trùng hoàn toàn với 9_49PM.wav.
Vì vậy, bộ nguồn có 15 bản ghi riêng biệt cho 16 đoạn; đoạn 16 vẫn dùng giọng đọc tiếng Anh của trình duyệt.

CÁCH ĐĂNG LÊN GITHUB
1. Tạo repository mới (ví dụ: abhiuyen-reading).
2. Giải nén ZIP. Upload index.html và toàn bộ thư mục mp3/ vào THƯ MỤC GỐC của repository.
3. Mở Settings > Pages. Ở Build and deployment, chọn Deploy from a branch.
4. Chọn branch main và folder /(root), rồi Save.
5. GitHub Pages sẽ xuất bản website tại https://<username>.github.io/<repo>/

Không đổi tên thư mục mp3 hoặc đường dẫn trong index.html.
Trang web không cần CDN hoặc thư viện bên ngoài.
Dùng để chạy local tốt nhất qua máy chủ tĩnh, ví dụ: python -m http.server 8000, sau đó mở http://localhost:8000/

# VBI NEW PRO – Ôn thi toàn tập

Ứng dụng web tiếng Việt tương thích GitHub Pages.

## Chức năng
- Giao diện responsive dạng Icon Grid.
- Ôn tập theo chủ đề và theo bộ đề.
- Thi thử độc lập 40 câu / 30 phút / ngưỡng đạt 30 câu; tự nộp khi hết giờ.
- Luyện câu sai, đánh dấu câu cần ôn, thống kê và lưu LocalStorage.
- Kiểm tra dữ liệu và manifest để bổ sung bộ đề trong tương lai.

## Dữ liệu nguồn
Bộ đề 01 và 02 đã được ghi nhận trong `assets/data/manifest.json`, trạng thái `pending_verification`. `assets/data/questions.json` cố ý để trống cho đến khi đối chiếu toàn bộ PDF đề gốc và tệp đáp án. Thi thử chỉ dùng các câu có `verificationStatus: verified`, và bị khóa nếu chưa đủ 40 câu.

## Triển khai GitHub Pages
Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Kiểm tra
`node tests/validation.js` kiểm tra cấu trúc JSON cơ bản; chưa thay thế đối chiếu nguồn hoặc kiểm thử trình duyệt thực tế.
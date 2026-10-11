# VBI NEW PRO – Ôn thi toàn tập

Ứng dụng web tiếng Việt, thiết kế responsive, chạy trên GitHub Pages.

## Các mục trong ứng dụng
- Ôn tập theo chủ đề và theo bộ đề gốc.
- Thi thử độc lập: 40 câu, 30 phút, đạt từ 30/40; tự nộp khi hết giờ.
- Luyện câu sai, đánh dấu câu cần ôn, thống kê và lưu tiến độ bằng LocalStorage.
- Báo cáo dữ liệu và manifest để thêm bộ đề mới.

## Dữ liệu chính thức
`assets/data/questions.json` hiện không chứa câu hỏi. Bộ đề 01 và 02 được ghi nhận trong `assets/data/manifest.json` với trạng thái `pending_verification`. Chỉ thêm câu sau khi đối chiếu PDF và đáp án DOCX. Chỉ câu có `verificationStatus: verified` mới được dùng trong thi thử; ứng dụng khóa thi thử nếu chưa đủ 40 câu đã xác minh.

## Triển khai
Workflow kiểm tra mã nguồn nằm tại `.github/workflows/static.yml`. Workflow GitHub Pages đã được tạo nhưng bước Deploy hiện thất bại do cấu hình/quyền Pages của repository; cần bật Pages trong Settings → Pages hoặc kiểm tra quyền Pages của GitHub Actions.

## Kiểm tra
`node tests/validation.js` kiểm tra cấu trúc JSON cơ bản, không thay thế việc đối chiếu dữ liệu gốc hoặc kiểm thử trình duyệt.
# Báo cáo đối chiếu dữ liệu nguồn — VBI NEW PRO

## Kết quả trích xuất

| Bộ đề | Số câu trong PDF | Số mục đáp án | Đã xác minh | Cần xác minh |
|---|---:|---:|---:|---:|
| 01 | 60 | 60 | 59 | 1 |
| 02 | 60 | 60 | 60 | 0 |
| 03 | 60 | 60 | 60 | 0 |
| 04 | 62 | 62 | 62 | 0 |
| 05 | 60 | 60 | 60 | 0 |
| 06 | 60 | 60 | 60 | 0 |
| 07 | 60 | 60 | 60 | 0 |
| 08 | 60 | 60 | 60 | 0 |
| **Tổng** | **482** | **482 mục câu hỏi/đáp án** | **481** | **1** |

## Câu cần xác minh

- **Bộ đề số 01 — Câu 25 (SET01-Q025):** tệp đáp án DOCX cung cấp phần trả lời dạng văn bản nhưng không ghi ký hiệu đáp án A/B/C/D/E. Phần nội dung này cũng không đủ để xác định chắc chắn một phương án duy nhất từ các lựa chọn trong PDF. Vì vậy bản ghi giữ nguyên câu hỏi và các phương án trích xuất, `correctAnswer` để `null`, trạng thái `needs-review`; ứng dụng không đưa câu này vào chế độ ôn tập/thi thử cho đến khi được xác minh.

## Nguyên tắc dữ liệu

- Mỗi câu giữ mã định danh theo bộ đề và số câu gốc, không gộp câu trùng giữa các bộ đề.
- Giữ số câu nguồn: 60 câu ở các bộ 01, 02, 03, 05, 06, 07, 08; 62 câu ở bộ 04.
- Đáp án chỉ được đánh dấu `verified` khi tệp đáp án có ký hiệu đáp án và ký hiệu đó xuất hiện trong danh sách phương án trích xuất từ PDF.
- Đây là kiểm tra trích xuất văn bản/đối chiếu ký hiệu. Cần kiểm tra thủ công các trang/ảnh có OCR hoặc bố cục bất thường trước khi khẳng định nguyên văn 100%.

## Tệp nguồn đã sử dụng

- Bộ 01: `1.1 BỘ ĐỀ SỐ 01 VBI NEW(2).pdf`
  - Đáp án: `1.1 Đáp án BỘ ĐỀ SỐ 01 VBI NEW(2).DOCX`
- Bộ 02: `2.1 BỘ ĐỀ SỐ 02 VBI NEW(2).pdf`
  - Đáp án: `2.2 Đáp án BỘ ĐỀ SỐ 02 VBI NEW(2).DOCX`
- Bộ 03: `3.1 BỘ ĐỀ SỐ 3 VBI NEW(2).pdf`
  - Đáp án: `3.2 Đáp án BỘ ĐỀ SỐ 3 VBI NEW(2).docx`
- Bộ 04: `4.1 BỘ ĐỀ SỐ 04 VBI NEW(6).pdf`
  - Đáp án: `4.2 Đáp án BỘ ĐỀ SỐ 04 VBI NEW(6).DOCX`
- Bộ 05: `5.1 BỘ ĐỀ SỐ 05 VBI NEW(2).pdf`
  - Đáp án: `5.2. Đáp án BỘ ĐỀ SỐ 05 VBI NEW(2).docx`
- Bộ 06: `6.1 BỘ ĐỀ SỐ 06 VBI NEW(2).pdf`
  - Đáp án: `6.1 Đáp án BỘ ĐỀ SỐ 06 VBI NEW(2).docx`
- Bộ 07: `7.1 BỘ ĐỀ SỐ 07 VBI NEW(2).pdf`
  - Đáp án: `7.2 Đáp án BỘ ĐỀ SỐ 07 VBI NEW(2).docx`
- Bộ 08: `8.1 BỘ ĐỀ SỐ 08 VBI NEW(2).pdf`
  - Đáp án: `8.2 BỘ ĐỀ SỐ 08 VBI NEW(2).DOCX`
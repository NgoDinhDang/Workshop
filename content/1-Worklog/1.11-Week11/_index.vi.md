---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11

* Triển khai các chức năng chính của dự án.
* Xây dựng luồng xử lý tài liệu tự động trên AWS.
* Kiểm thử quá trình xử lý tài liệu sau khi tải lên Amazon S3.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Xây dựng chức năng tải tệp ảnh/PDF từ Frontend lên Amazon S3.<br>- Kiểm tra quá trình lưu trữ tệp trên S3. | 29/06/2026 | 29/06/2026 | https://docs.aws.amazon.com/s3/ |
| 3 | - Cấu hình Amazon S3 Event Notification.<br>- Kết nối S3 với AWS Lambda để tự động xử lý khi có tệp mới. | 30/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 4 | - Phát triển AWS Lambda để tiếp nhận sự kiện từ Amazon S3.<br>- Kiểm tra quá trình kích hoạt Lambda sau khi tải tệp lên. | 01/07/2026 | 01/07/2026 | https://docs.aws.amazon.com/lambda/ |
| 5 | - Tích hợp Amazon Textract để trích xuất nội dung văn bản từ ảnh và tài liệu PDF.<br>- Kiểm thử kết quả OCR trên một số tài liệu mẫu. | 02/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/textract/ |
| 6 | - Kiểm tra toàn bộ luồng xử lý từ Amazon S3 → AWS Lambda → Amazon Textract.<br>- Ghi nhận kết quả và điều chỉnh cấu hình khi cần thiết. | 03/07/2026 | 03/07/2026 | https://www.youtube.com/@AWSStudyGroup |

### Kết quả đạt được tuần 11

* Hoàn thành chức năng tải tệp từ Frontend lên Amazon S3.

* Cấu hình thành công Amazon S3 Event Notification để kích hoạt AWS Lambda.

* Xây dựng được hàm AWS Lambda tiếp nhận và xử lý sự kiện từ Amazon S3.

* Tích hợp Amazon Textract để trích xuất văn bản từ ảnh và tài liệu PDF.

* Kiểm thử thành công luồng xử lý:

  * Frontend
  * Amazon S3
  * S3 Event Notification
  * AWS Lambda
  * Amazon Textract

* Hoàn thiện nền tảng cho giai đoạn tích hợp AI và lưu trữ dữ liệu ở tuần tiếp theo.
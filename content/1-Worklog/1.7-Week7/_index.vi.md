---
title: "Nhật ký công việc tuần 7"
date: 2026-07-30
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Mục tiêu tuần 7:

* Tích hợp AWS S3 để lưu trữ file/tài liệu phục vụ các tính năng backend.
* Di chuyển cơ sở dữ liệu của ứng dụng sang dịch vụ cơ sở dữ liệu được quản lý của AWS (RDS/DynamoDB) để tăng khả năng mở rộng.

### Các nhiệm vụ cần thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu các khái niệm của S3<br>&emsp; + Bucket<br>&emsp; + Object<br>&emsp; + Quyền truy cập<br>- Tạo S3 bucket, cấu hình bucket policy & CORS | 13/07/2026 | 13/07/2026 | https://docs.aws.amazon.com/s3/ |
| 3 | - Tích hợp AWS SDK vào backend để upload/download file<br>- Triển khai các endpoint upload file được ứng dụng sử dụng | 14/07/2026 | 14/07/2026 |  |
| 4 | - Nghiên cứu RDS và DynamoDB, đánh giá lựa chọn nào phù hợp nhất với mô hình dữ liệu hiện tại<br>- Tạo RDS instance / DynamoDB table, cấu hình bảo mật | 15/07/2026 | 15/07/2026 | https://docs.aws.amazon.com/rds/ |
| 5 | - Di chuyển schema/dữ liệu từ cơ sở dữ liệu tự triển khai sang cơ sở dữ liệu được quản lý<br>- Cập nhật ứng dụng backend để kết nối với dịch vụ cơ sở dữ liệu mới | 16/07/2026 | 16/07/2026 |  |
| 6 | - Kiểm thử upload/download file và kết nối cơ sở dữ liệu sau khi di chuyển<br>- Tối ưu truy cập file (presigned URL) và theo dõi hiệu năng cơ sở dữ liệu | 17/07/2026 | 17/07/2026 |  |

### Thành tích tuần 7:

* Hiểu được các khái niệm cốt lõi của S3 và tạo được S3 bucket cấu hình đúng để lưu trữ file của ứng dụng.
* Triển khai các endpoint upload/download file sử dụng AWS SDK và S3.
* So sánh RDS và DynamoDB dựa trên mô hình dữ liệu thực tế của dự án và chọn ra phương án phù hợp hơn.
* Di chuyển thành công cơ sở dữ liệu từ tự triển khai sang dịch vụ cơ sở dữ liệu được quản lý của AWS mà không mất dữ liệu.
* Cập nhật và kiểm thử lại ứng dụng backend với cơ sở dữ liệu mới, xác nhận hiệu năng ổn định.

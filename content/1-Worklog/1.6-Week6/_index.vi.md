---
title: "Worklog Tuần 6"
date: 2026-02-09
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Chốt loại database sử dụng cho hệ thống.  
* Triển khai database trên AWS (Amazon RDS).  
* Tích hợp ORM (Prisma) vào backend.  
* Chuẩn hóa và refactor lại backend theo database mới.  
* Xây dựng chức năng xác thực người dùng (Authentication).  
* Bắt đầu định hướng tích hợp AI vào hệ thống.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Quyết định lựa chọn database: <br>&emsp; + PostgreSQL <br> - Lý do lựa chọn: phù hợp với dữ liệu có cấu trúc và quan hệ rõ ràng | 09/02/2026 | 09/02/2026 | |
| 3 | - Tìm hiểu và triển khai database trên AWS: <br>&emsp; + Amazon RDS <br> - Tạo instance PostgreSQL <br> - Kết nối database với backend | 10/02/2026 | 10/02/2026 | |
| 4 | - Cài đặt và cấu hình Prisma ORM <br> - Thiết kế schema Prisma <br> - Thực hiện migrate database | 11/02/2026 | 11/02/2026 | |
| 5 | - Refactor backend theo Prisma: <br>&emsp; + Cập nhật model <br>&emsp; + Cập nhật controller <br> - Đảm bảo các API hoạt động với database mới | 12/02/2026 | 12/02/2026 | |
| 6 | - Xây dựng Authentication: <br>&emsp; + API register <br>&emsp; + API login <br> - Tìm hiểu JWT (JSON Web Token) <br> - Test toàn bộ hệ thống (API + DB + frontend) | 13/02/2026 | 13/02/2026 | |


### Kết quả đạt được tuần 6:
* Quyết định sử dụng PostgreSQL làm database chính cho hệ thống.  

* Lựa chọn triển khai database trên AWS:
  * Amazon RDS  

* Triển khai thành công database trên AWS  

* Kết nối backend với database hoạt động ổn định  

* Tích hợp Prisma ORM vào backend:
  * Thiết kế schema  
  * Thực hiện migrate database  
  * Thực hiện truy vấn dữ liệu thông qua Prisma  

* Refactor backend:
  * Đồng bộ với database mới  
  * Đảm bảo các API hoạt động ổn định  

* Xây dựng chức năng xác thực người dùng:
  * API đăng ký (register)  
  * API đăng nhập (login)  

* Bước đầu hiểu cơ chế:
  * Xác thực bằng JWT  

* Kiểm tra và đảm bảo hoạt động của hệ thống:
  * Frontend gọi API thành công  
  * Backend xử lý logic  
  * Database lưu trữ dữ liệu  

* Hiểu rõ hơn flow tổng thể của hệ thống:
  * Frontend → Backend → Database → Response  

* Bắt đầu định hướng tích hợp AI:
  * Phân tích luồng dữ liệu giữa người dùng và hệ thống  
  * Xem xét cách sử dụng dữ liệu cho việc gợi ý sản phẩm và chatbot  




---
title: "Worklog Tuần 11"
date: 2026-03-23
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---



### Mục tiêu tuần 11:

* Triển khai toàn bộ hệ thống lên AWS.  
* Cấu hình hạ tầng cloud theo kiến trúc đã thiết kế.  
* Đảm bảo hệ thống có thể truy cập từ internet.  
* Thiết lập giám sát và theo dõi hệ thống.  
* Kiểm thử hệ thống sau khi triển khai.  

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Build Docker image cho backend <br>&emsp; + Cấu hình Dockerfile <br>&emsp; + Kiểm tra chạy container local | 23/03/2026 | 23/03/2026 | |
| 3 | - Đẩy image lên AWS: <br>&emsp; + Tạo repository trên Amazon ECR <br>&emsp; + Push Docker image lên ECR | 24/03/2026 | 24/03/2026 | |
| 4 | - Deploy backend: <br>&emsp; + Cấu hình ECS (Fargate) <br>&emsp; + Tạo service và task definition | 25/03/2026 | 25/03/2026 | |
| 5 | - Cấu hình Application Load Balancer: <br>&emsp; + Route request tới ECS <br>&emsp; + Mở port và cấu hình Security Group | 26/03/2026 | 26/03/2026 | |
| 6 | - Deploy frontend: <br>&emsp; + Build React app <br>&emsp; + Upload lên S3 <br>&emsp; + (Optional) cấu hình CloudFront CDN <br> - Thiết lập CloudWatch để theo dõi log | 27/03/2026 | 27/03/2026 | |


### Kết quả đạt được tuần 11:

* Triển khai backend lên AWS:
  * Build Docker image  
  * Push lên Amazon ECR  
  * Deploy thành công trên ECS (Fargate)  

* Cấu hình hệ thống mạng:
  * Application Load Balancer điều hướng request  
  * Cấu hình Security Group cho phép truy cập từ internet  

* Triển khai frontend:
  * Build ứng dụng React  
  * Deploy lên S3 (static hosting)  
  * (Tùy chọn) sử dụng CloudFront để tối ưu tốc độ truy cập  

* Thiết lập giám sát hệ thống:
  * Sử dụng CloudWatch để theo dõi log backend  
  * Kiểm tra trạng thái service  

* Kiểm thử hệ thống sau khi deploy:
  * Truy cập hệ thống qua internet  
  * Kiểm tra luồng người dùng (xem sản phẩm, thêm giỏ, đặt hàng)  
  * Kiểm tra luồng quản trị (admin)  
  * Đảm bảo các module hoạt động ổn định  

* Hiểu rõ quy trình triển khai hệ thống:
  * Code → Docker → ECR → ECS → ALB → User  



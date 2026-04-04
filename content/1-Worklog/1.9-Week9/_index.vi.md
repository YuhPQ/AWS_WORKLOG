---
title: "Worklog Tuần 9"
date: 2026-03-09
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---



### Mục tiêu tuần 9:

* Chuẩn hóa và tối ưu backend hệ thống.  
* Xây dựng cơ chế phân quyền (User / Admin).  
* Phát triển các API phục vụ quản trị hệ thống (Admin).  
* Đảm bảo hệ thống sẵn sàng tích hợp với các module bên ngoài (AI, chatbot).  
* Kiểm tra và cải thiện hiệu năng toàn hệ thống.  


### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Refactor backend: <br>&emsp; + Tách rõ controller / service <br>&emsp; + Chuẩn hóa response API <br> - Xử lý lỗi (error handling) | 09/03/2026 | 09/03/2026 | |
| 3 | - Xây dựng cơ chế phân quyền: <br>&emsp; + Phân biệt User và Admin <br>&emsp; + Middleware kiểm tra quyền truy cập | 10/03/2026 | 10/03/2026 | |
| 4 | - Phát triển API quản lý sản phẩm (Admin): <br>&emsp; + Create product <br>&emsp; + Update product <br>&emsp; + Delete product | 11/03/2026 | 11/03/2026 | |
| 5 | - Hoàn thiện API tìm kiếm và lọc sản phẩm: <br>&emsp; + Search theo tên <br>&emsp; + Filter theo category, skin_type | 12/03/2026 | 12/03/2026 | |
| 6 | - Kiểm tra và tối ưu hệ thống: <br>&emsp; + Validate input <br>&emsp; + Tối ưu query database <br>&emsp; + Fix bug toàn hệ thống | 13/03/2026 | 13/03/2026 | |


### Kết quả đạt được tuần 9:

* Chuẩn hóa backend:
  * Tách rõ controller và service  
  * Chuẩn hóa cấu trúc response API  
  * Xử lý lỗi trong hệ thống  

* Xây dựng cơ chế phân quyền:
  * Phân biệt User và Admin  
  * Bảo vệ các API quan trọng bằng middleware  

* Phát triển API quản trị:
  * Admin có thể thêm, sửa, xóa sản phẩm  
  * Hỗ trợ quản lý dữ liệu trong hệ thống  

* Hoàn thiện chức năng tìm kiếm và lọc:
  * Tìm kiếm sản phẩm theo tên  
  * Lọc theo category và loại da  

* Tối ưu hệ thống:
  * Kiểm tra và validate dữ liệu đầu vào  
  * Tối ưu truy vấn database  
  * Fix các lỗi phát sinh trong quá trình sử dụng  

* Chuẩn bị tích hợp với các module bên ngoài:
  * Xây dựng các API phục vụ việc truy xuất dữ liệu sản phẩm  
  * Đảm bảo hệ thống sẵn sàng tích hợp với AI và chatbot  


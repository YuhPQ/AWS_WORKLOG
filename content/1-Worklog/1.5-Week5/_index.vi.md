---
title: "Worklog Tuần 5"
date: 2026-02-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Hoàn thiện thiết kế database và bổ sung các field còn thiếu.  
* Tiếp tục phân tích và lựa chọn loại database phù hợp (SQL vs NoSQL).  
* Tìm hiểu các dịch vụ database trên AWS (RDS, DynamoDB).  
* Kết nối frontend với backend API.  
* Hiển thị dữ liệu sản phẩm trên giao diện người dùng. 

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Tiếp tục hoàn thiện thiết kế database <br>&emsp; + Bổ sung field cho Product (name, price, description, image, skin_type, ...) <br>&emsp; + Xem xét thêm các entity (User, Category) | 02/02/2026 | 02/02/2026 | |
| 3 | - Tìm hiểu và so sánh database: <br>&emsp; + SQL (PostgreSQL, MySQL) <br>&emsp; + NoSQL (MongoDB) <br> - Đánh giá theo tiêu chí: <br>&emsp; + Cấu trúc dữ liệu <br>&emsp; + Khả năng mở rộng <br>&emsp; + Phù hợp với hệ thống | 03/02/2026 | 03/02/2026 | |
| 4 | - Tìm hiểu các dịch vụ database trên AWS: <br>&emsp; + Amazon RDS <br>&emsp; + Amazon DynamoDB <br> - So sánh cách triển khai database trên cloud | 04/02/2026 | 04/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Kết nối frontend (React) với backend API <br> - Gọi API lấy danh sách sản phẩm (GET /products) <br> - Hiển thị dữ liệu sản phẩm trên giao diện | 05/02/2026 | 05/02/2026 | |
| 6 | - Tiếp tục cải thiện UI cơ bản <br> - Kiểm tra và xử lý lỗi khi gọi API <br> - Refactor code frontend và backend | 06/02/2026 | 06/02/2026 | |



### Kết quả đạt được tuần 5:

* Tiếp tục hoàn thiện thiết kế database:
  * Bổ sung các field cần thiết cho Product  
  * Xác định thêm các entity như User, Category  

* Tìm hiểu và so sánh các loại database:
  * SQL (quan hệ)
  * NoSQL (phi quan hệ)

* Phân tích được:
  * SQL: phù hợp với dữ liệu có cấu trúc rõ ràng và quan hệ chặt chẽ  
  * NoSQL: linh hoạt, dễ mở rộng  

* Tìm hiểu các dịch vụ database trên AWS:
  * Amazon RDS  
  * Amazon DynamoDB  

* Bước đầu hiểu:
  * Sự khác nhau giữa managed database (RDS) và NoSQL service (DynamoDB) 

* Kết nối thành công frontend với backend  

* Thực hiện được:
  * Gọi API từ frontend  
  * Hiển thị danh sách sản phẩm trên giao diện  

* Hiểu được flow hoạt động:
  * Frontend → API → Backend → Database → Response → UI  

* Bắt đầu hình dung rõ hơn cách các thành phần trong hệ thống tương tác với nhau  


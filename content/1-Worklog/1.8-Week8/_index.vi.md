---
title: "Worklog Tuần 8"
date: 2026-03-02
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---



### Mục tiêu tuần 8:

* Hoàn thiện luồng mua hàng (Checkout Flow).  
* Xây dựng hệ thống đơn hàng (Order System).  
* Lưu trữ và quản lý lịch sử đơn hàng.  
* Tích hợp lưu trữ hình ảnh bằng AWS S3.  
* Bắt đầu áp dụng mã giảm giá (Coupon) trong quá trình thanh toán (mức cơ bản).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Thiết kế luồng Checkout: <br>&emsp; + Nhập thông tin người nhận <br>&emsp; + Địa chỉ giao hàng <br> - Xây dựng UI trang Checkout | 02/03/2026 | 02/03/2026 | |
| 3 | - Xây dựng API tạo đơn hàng: <br>&emsp; + Tạo Order <br>&emsp; + Tạo OrderDetail <br> - Lưu dữ liệu vào database | 03/03/2026 | 03/03/2026 | |
| 4 | - Xây dựng chức năng đặt hàng: <br>&emsp; + Từ giỏ hàng → tạo đơn hàng <br>&emsp; + Xóa/clear giỏ hàng sau khi đặt thành công | 04/03/2026 | 04/03/2026 | |
| 5 | - Xây dựng lịch sử đơn hàng: <br>&emsp; + API lấy danh sách đơn hàng <br>&emsp; + Hiển thị trên frontend | 05/03/2026 | 05/03/2026 | |
| 6 | - Tích hợp AWS S3: <br>&emsp; + Upload ảnh sản phẩm <br>&emsp; + Lưu URL vào database <br> - Tìm hiểu áp dụng mã giảm giá khi checkout (basic) | 06/03/2026 | 06/03/2026 | |


### Kết quả đạt được tuần 8:

* Hoàn thiện luồng Checkout:
  * Người dùng nhập thông tin giao hàng  
  * Xác nhận đơn hàng trước khi đặt  

* Xây dựng hệ thống đơn hàng:
  * Tạo Order  
  * Tạo OrderDetail  
  * Lưu dữ liệu vào database  

* Xây dựng chức năng đặt hàng:
  * Chuyển dữ liệu từ Cart → Order  
  * Xóa giỏ hàng sau khi đặt thành công  

* Xây dựng lịch sử đơn hàng:
  * Hiển thị danh sách đơn hàng của người dùng  
  * Lấy dữ liệu từ database  

* Tích hợp lưu trữ hình ảnh bằng AWS:
  * Upload ảnh lên S3  
  * Lưu URL ảnh vào database  
  * Hiển thị ảnh từ S3 trên frontend  

* Bắt đầu áp dụng mã giảm giá:
  * Tìm hiểu cách áp dụng coupon trong quá trình checkout  
  * Xây dựng logic cơ bản (chưa hoàn thiện)  

* Hiểu rõ luồng hoạt động của hệ thống:
  * Cart → Checkout → Order → Database → UI  




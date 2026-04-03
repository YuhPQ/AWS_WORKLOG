---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---



### Mục tiêu tuần 7:

* Hoàn thiện trải nghiệm người dùng trong hệ thống e-commerce.  
* Xây dựng và hoàn thiện chức năng giỏ hàng (Cart System).  
* Đảm bảo đồng bộ dữ liệu giữa frontend và backend.  
* Nâng cấp giao diện sản phẩm và luồng mua hàng.  
* Bắt đầu tìm hiểu hệ thống mã giảm giá (Coupon).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2 | - Hoàn thiện chức năng xác thực người dùng: <br>&emsp; + Login / Register flow <br>&emsp; + Lưu JWT trên frontend <br> - Phân biệt user và guest khi sử dụng hệ thống | 22/09/2025 | 22/09/2025 | |
| 3 | - Xây dựng giao diện sản phẩm: <br>&emsp; + Trang danh sách sản phẩm <br>&emsp; + Trang chi tiết sản phẩm <br> - Hiển thị đầy đủ thông tin (ảnh, giá, mô tả, loại da) | 23/09/2025 | 23/09/2025 | |
| 4 | - Xây dựng chức năng giỏ hàng (Guest mode): <br>&emsp; + Thêm sản phẩm vào giỏ (LocalStorage) <br>&emsp; + Hiển thị số lượng trên icon giỏ hàng <br> - Cải thiện UX: loading state, toast notification | 24/09/2025 | 24/09/2025 | |
| 5 | - Nâng cấp giỏ hàng: <br>&emsp; + Chống spam khi click (disable button) <br>&emsp; + Giới hạn số lượng sản phẩm (max = 5) <br> - Xây dựng chức năng tăng/giảm/xóa sản phẩm | 25/09/2025 | 25/09/2025 | |
| 6 | - Đồng bộ dữ liệu giỏ hàng: <br>&emsp; + Merge LocalStorage → Database khi đăng nhập <br>&emsp; + Cập nhật dữ liệu theo thời gian thực (real-time sync) <br> - Tìm hiểu cơ chế mã giảm giá (Coupon) | 26/09/2025 | 26/09/2025 | |


### Kết quả đạt được tuần 7:

* Hoàn thiện chức năng xác thực:
  * Người dùng có thể đăng ký và đăng nhập  
  * Lưu JWT và sử dụng trong các request  

* Xây dựng giao diện sản phẩm:
  * Trang danh sách sản phẩm  
  * Trang chi tiết sản phẩm  
  * Hiển thị đầy đủ thông tin sản phẩm  

* Xây dựng hệ thống giỏ hàng:

* Hỗ trợ Guest mode:
  * Lưu dữ liệu giỏ hàng bằng LocalStorage  

* Cải thiện trải nghiệm người dùng:
  * Hiển thị trạng thái loading khi thao tác  
  * Thông báo (toast) khi thêm sản phẩm  
  * Chống spam khi click (disable button)  

* Giới hạn và kiểm soát dữ liệu:
  * Giới hạn tối đa 5 sản phẩm cho mỗi item  
  * Xử lý tăng/giảm/xóa sản phẩm trong giỏ  

* Đồng bộ dữ liệu giỏ hàng:
  * Merge dữ liệu từ LocalStorage vào Database khi đăng nhập  
  * Cập nhật dữ liệu theo thời gian thực (save-on-click)  

* Đảm bảo tính nhất quán dữ liệu:
  * Frontend (LocalStorage)  
  * Backend  
  * Database (Prisma)  

* Kiểm tra và đảm bảo các luồng hoạt động:
  * Guest thêm sản phẩm vào giỏ  
  * Người dùng đăng nhập và giữ nguyên giỏ hàng  
  * Thao tác giỏ hàng được cập nhật chính xác  

* Bắt đầu tìm hiểu hệ thống mã giảm giá:
  * Cách lưu trữ coupon trong database  
  * Cách áp dụng mã giảm giá cho người dùng  




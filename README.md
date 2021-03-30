# Quy trình nhận và hỗ trợ chấm thi giáo viên dạy giỏi
Quy trình nhận và hỗ trợ chấm thi giáo viên dạy giỏi

# 1. Chuẩn bị
- 1 tài khoản Office 365 có license A1 hoặc cao hơn.
- Tài liệu: https://github.com/Office365VietNam-info/Nop-bai-thi-GV-day-gioi

# 2. Kiến trúc xử lý
![alt text](https://github.com/Office365VietNam-info/Nop-bai-thi-GV-day-gioi/blob/main/Architecture/Architecture.png?raw=true)

# 3. Các bước làm
a. Tạo Forms
Tạo Forms để nhận kết quả dự thi, forms mẫu như hình bên dưới:
![alt text](https://github.com/Office365VietNam-info/Nop-bai-thi-GV-day-gioi/blob/main/Images/Forms%20mau.png?raw=true)

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/mTmKMMafNWs/maxresdefault.jpg)](https://youtu.be/mTmKMMafNWs)

b. Tạo nhóm trên Teams
Tạo 1 nhóm trên Teams có các kênh:
- Thông báo(chế độ: standard): để gửi thông báo khi có sản phẩm dự thi được nộp.
- Nộp sản phẩm dự thi(chế độ: private): để lưu thông tin dự thi và thư mục chứa sản phẩm dự thi.
- Các kênh giành cho giám khảo 1,2 3(chế độ: private): để lưu thông tin dự thi và thư mục chứa sản phẩm dự thi cho từng giám khảo.
Mẫu tham khảo như hình dưới:
![alt text](https://github.com/Office365VietNam-info/Nop-bai-thi-GV-day-gioi/blob/main/Images/Teams.png?raw=true)

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/J--UchXEFlk/maxresdefault.jpg)](https://youtu.be/J--UchXEFlk)

c. Tạo trang Sharepoint site
Tạo 1 trang SharePoint site để lưu thông tin đăng ký từ forms và lưu sản phẩn dự thi.
Tạo SharePoint list: 
- Nộp bài thi.
- Giám khảo 1,2 và 3.
Mẫu các cột thông tin cần thiết tại https://github.com/Office365VietNam-info/Nop-bai-thi-GV-day-gioi/tree/main/SharePoint

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/7jn4C8pqKmo/maxresdefault.jpg)](https://youtu.be/7jn4C8pqKmo)

d. Hoàn chỉnh giao diện trên teams
Thêm các apps vào nhóm Teams đã tạo ở trên để quản lý.
- Kênh **Nộp sản phẩm dự thi** thêm **Lists**(chứa thông tin SharePoint list **Nộp bài thi**) và **Document Library**(là thông tin Documents trong trang SharePoint đã tạo)
- Các kênh cho **Giám khảo 1, 2 và 3** thêm **Lists**(chứa thông tin SharePoint list **Giám khảo 1, 2 và 3**) và **Document Library**(là thông tin Documents trong trang SharePoint đã tạo)

Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/Y43JbfVH-Jg/maxresdefault.jpg)](https://youtu.be/Y43JbfVH-Jg)

e. Cập nhật các gói PowerAutomate
- Cập nhật flow: Nộp sản phẩm
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)

- Cập nhật flow: Sao chép tập tin
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/3Gkv-ysHoUI/maxresdefault.jpg)](https://youtu.be/3Gkv-ysHoUI)

- Cập nhật flow: Phân công chấm thi
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)

- Tổng hợp thông tin chấm thi Giám khảo 1
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)

- Tổng hợp thông tin chấm thi Giám khảo 2
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)

- Tổng hợp thông tin chấm thi Giám khảo 3
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)

- Kiểm thử và chỉnh sửa
Video hướng dẫn:
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)

- Phân quyền bổ sung
[![Watch the video](https://img.youtube.com/vi/IekGYklcO5k/maxresdefault.jpg)](https://youtu.be/IekGYklcO5k)


Chúc các bạn thành công và có thể tùy chỉnh để có thể áp dụng cho nhiều mục đích khác trong tổ chức!

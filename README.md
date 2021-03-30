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

b. Tạo nhóm trên Teams
Tạo 1 nhóm trên Teams có các kênh:
- Thông báo(chế độ: standard): để gửi thông báo khi có sản phẩm dự thi được nộp.
- Nộp sản phẩm dự thi(chế độ: private): để lưu thông tin dự thi và thư mục chứa sản phẩm dự thi.
- Các kênh giành cho giám khảo 1,2 3(chế độ: private): để lưu thông tin dự thi và thư mục chứa sản phẩm dự thi cho từng giám khảo.
Mẫu tham khảo như hình dưới:
![alt text](https://github.com/Office365VietNam-info/Nop-bai-thi-GV-day-gioi/blob/main/Images/Teams.png?raw=true)

c. Tạo trang Sharepoint site

d. Hoàn chỉnh giao diện trên teams

e. Cập nhật các gói PowerAutomate
- Cập nhật flow: Nộp sản phẩm
- Cập nhật flow: Sao chép tập tin
- Cập nhật flow: Phân công chấm thi
- Tổng hợp thông tin chấm thi Giám khảo 1
- Tổng hợp thông tin chấm thi Giám khảo 2
- Tổng hợp thông tin chấm thi Giám khảo 3
- Kiểm thử và chỉnh sửa
- Phân quyền bổ sung

# Nhan_dien_deo_khau_trang
## 📌 Giới thiệu
Hệ thống sử dụng **Trí tuệ nhân tạo (AI)** và **Thị giác máy tính (Computer Vision)** để nhận diện tình trạng đeo khẩu trang của người dùng trong ảnh hoặc video.  
Ứng dụng có thể phân loại:
- ✅ Có khẩu trang  
- ❌ Không khẩu trang  
- ⚠️ Đeo sai cách  

## ⚙️ Chức năng chính
- Nhận diện khuôn mặt từ ảnh hoặc camera thời gian thực.  
- Phân loại trạng thái đeo khẩu trang bằng mô hình AI (`MaskDetector`).  
- Lưu lịch sử nhận diện vào cơ sở dữ liệu (`History`).  
- Cho phép **quản trị viên** xem, xuất hoặc xóa lịch sử.  

## 🏗️ Cấu trúc hệ thống
- **User**: Quản lý tài khoản và phân quyền.  
- **History**: Lưu trữ thông tin kết quả (ngày, giờ, trạng thái).  
- **MaskDetector**: Chứa mô hình AI và phương thức dự đoán.  

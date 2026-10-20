# LAB 7 – Xây dựng chính sách Web Protection

**Họ và tên:** Lê Quốc Huy  
**MSSV:** 1150070016  
**Mã lớp:** TTMT  
**Môn học:** Thực hành An toàn Hệ thống Thông tin  

## Giới thiệu

Bài thực hành Lab 7 triển khai chính sách kiểm soát truy cập Web với pfSense và Web Proxy. pfSense quản lý lưu lượng mạng, còn Squid và E2Guardian lọc truy cập, áp dụng danh sách cho phép hoặc chặn, hiển thị cảnh báo và ghi nhật ký.

## Mục tiêu

- Cấu hình pfSense làm firewall và gateway cho mạng lab.
- Cài đặt Squid và E2Guardian trên Ubuntu Server.
- Thiết lập các chính sách chặn, cảnh báo và whitelist.
- Kiểm tra việc chặn truy cập Web trực tiếp khi client không dùng proxy.
- Theo dõi log và thử quét tệp tải xuống bằng ClamAV.
- Tìm hiểu HTTPS inspection trong môi trường máy ảo.

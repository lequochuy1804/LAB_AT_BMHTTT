# LAB 8 – LOCAL DNS ATTACK DNS SPOOFING VÀ CACHE POISONING TRÊN MÔ HÌNH pfSense
Họ và tên: Lê Quốc Huy  
MSSV: 1150070016  
Lớp: TTMT  
## Mục tiêu
Tìm hiểu cơ chế phân giải tên miền DNS, thực hành giả mạo phản hồi DNS và đầu độc bộ nhớ đệm DNS trong mạng máy ảo cô lập; phân tích kết quả và các biện pháp phòng chống.
## Nội dung bài thực hành
- Xây dựng mạng DNS-LAB riêng phía sau pfSense.
- Cấu hình DNS Server BIND9, máy Victim và Kali Linux.
- Kiểm tra phân giải tên miền hợp lệ trước khi thử nghiệm.
- Task 1: Thay đổi file hosts để chuyển hướng tên miền sang website giả lập.
- Task 2: Giả mạo phản hồi DNS trực tiếp đến máy Victim.
- Task 3: Đầu độc cache DNS Server và kiểm tra bản ghi sai trong bộ nhớ đệm.
- Sử dụng Wireshark để quan sát và phân tích các gói tin DNS.
- Khôi phục cấu hình, xóa cache và tìm hiểu các biện pháp bảo vệ DNS.

# LAB 6: XÁC THỰC ACTIVE DIRECTORY VÀ CHÍNH SÁCH TRUY CẬP TRÊN pfSense

- **Họ và tên:** Lê Quốc Huy
- **MSSV:** 1150070016
- **Mã lớp:** TTMT
- **Môn học:** Thực hành An toàn Hệ thống Thông tin

---

## 1. Thông tin Môi trường Lab (Topology)
Mô hình bài Lab bao gồm 4 phân vùng mạng chính trên pfSense:
- **WAN (em0):** 192.168.250.0/24 (DHCP - Kết nối Internet)
- **MGMT (em2):** 192.168.56.254/24 (Host-Only - Dành riêng quản trị WebGUI pfSense)
- **LAN (em1):** 10.6.0.1/24 (Internal Network lab6-lan - Mạng Domain)
- **DMZ (em3):** 172.16.6.1/24 (Internal Network lab6-dmz - Mạng Web Server)

### Địa chỉ IP các máy trạm & Máy chủ:
- **DC01:** 10.6.0.10/24 (Windows Server - AD DS domain lab6.test, DNS Server)
- **Client-A:** 10.6.0.21/24 (Windows 11 - User sv_a)
- **Client-B:** 10.6.0.22/24 (Windows 11 - User sv_b)
- **DMZ-WEB:** 172.16.6.10/24 (Ubuntu Server running Nginx)
  - 172.16.6.10: GENERAL_SITE
  - 172.16.6.20: JOB_SITE
  - 172.16.6.30: SOCIAL_SITE
  - 172.16.6.40: RESTRICTED_SITE

---
## 2. Tệp tin Đính kèm
- **Báo cáo chi tiết (Word):** TTMT-Lab6_1150070016-LeQuocHuy.docx
- **Cấu hình pfSense:** config.xml

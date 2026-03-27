# Enterprise-Network-Simulation-Ha-Dong-Cau-Giay-via-PKT
Simulated a multi-branch network (Ha Dong - Cau Giay) by configuring VLANs, RIPv2 routing, and essential services (DHCP, Mail, Web) to ensure cross-branch connectivity.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0a1ed099-9c18-4d14-9988-5b542cec9805" />
Hệ thống mạng được thiết kế theo mô hình 3 lớp (Core - Distribution - Access) kết nối qua WAN, bao gồm 3 khu vực chính:
1.	Trung tâm dữ liệu (Server ): Nơi đặt các máy chủ dịch vụ (Web, DHCP, DNS).
2.	Chi nhánh Cầu Giấy (Site A): Sử dụng dải mạng 192.168.2.0.
3.	Chi nhánh Hà Đông (Site B): Sử dụng dải mạng 192.168.3.0.
Các chi nhánh được kết nối với trung tâm thông qua Router sử dụng giao thức định tuyến động RIPv2.

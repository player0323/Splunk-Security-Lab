# Project: SSH Brute Force Detection with Splunk

## 1. Giới thiệu (Introduction)
Dự án này tập trung vào việc xây dựng hệ thống giám sát an ninh (SIEM) sử dụng Splunk Enterprise để phát hiện các cuộc tấn công Brute Force qua giao thức SSH.
Mục tiêu là mô phỏng lại quá trình tấn công thực tế và thiết lập các cảnh báo tự động.

## 2. Mô hình Lab (Architecture)
*(Sẽ chèn hình ảnh sơ đồ mạng ở đây sau)*

## 3. Công nghệ sử dụng (Tech Stack)
- **SIEM:** Splunk Enterprise
- **Attacker:** Kali Linux (Hydra)
- **Victim:** Ubuntu Server
- **Log Source:** /var/log/auth.log (Linux Secure Log)

## 4. Kế hoạch thực hiện (Roadmap)
- [ ] Cài đặt môi trường Lab.
- [ ] Thực hiện tấn công giả lập.
- [ ] Cấu hình Log Ingestion vào Splunk.
- [ ] Viết câu lệnh truy vấn (SPL) để phát hiện tấn công.
- [ ] Tạo Dashboard và Alert.
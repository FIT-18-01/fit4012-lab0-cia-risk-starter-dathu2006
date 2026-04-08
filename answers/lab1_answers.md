# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đoàn Quốc Bảo

**MSSV:** 1871020071

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu khách hàng (Customer Data) – Bao gồm thông tin cá nhân, mật khẩu, và lịch sử giao dịch.
- Asset 2:Mã nguồn ứng dụng (Source Code) – Tài sản trí tuệ quan trọng giúp hệ thống vận hành.
- Asset 3:Hệ thống máy chủ (Server Infrastructure) – Phần cứng và phần mềm nền tảng để duy trì dịch vụ trực tuyến.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A (Rò rỉ dữ liệu ra ngoài) -> Confidentiality (Tính bảo mật): Thông tin bị người không có thẩm quyền truy cập.
- Sự cố B (Dữ liệu bị virus mã hóa hoặc sửa đổi trái phép) -> Integrity (Tính toàn vẹn): Dữ liệu không còn chính xác hoặc đã bị thay đổi.
- Sự cố C (Hệ thống bị tấn công từ chối dịch vụ DDoS) -> Availability (Tính khả dụng): Người dùng hợp pháp không thể truy cập vào dịch vụ.

---

## 3. Phân tích sự cố B
- Threat: Mã độc (Ransomware) hoặc Hacker có ý đồ phá hoại dữ liệu.
- Vulnerability: Hệ điều hành chưa được cập nhật bản vá bảo mật, hoặc nhân viên vô tình nhấn vào link lạ trong Email (Phishing).
- Mitigation: Triển khai phần mềm diệt virus bản quyền, thực hiện sao lưu dữ liệu (Backup) định kỳ và đào tạo nhận thức an toàn thông tin cho người dùng.

---

## 4. Reflection
- Hiểu rõ bộ ba nguyên tắc CIA: Bảo mật, Toàn vẹn và Sẵn sàng.
- Nhận thức được tầm quan trọng của việc xác định đúng tài sản (Assets).
- Biết cách phân loại các mối đe dọa (Threats) phổ biến hiện nay.
- Tự xác định được các lỗ hổng (Vulnerabilities) thường gặp trong hệ thống.
- Học được các biện pháp giảm nhẹ (Mitigation) như phân quyền và mã hóa.
- Nâng cao ý thức bảo mật khi thiết kế và vận hành các ứng dụng phần mềm.
- Đây là nền tảng quan trọng giúp em xây dựng các hệ thống an toàn hơn.

---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-C-B-I-C-A}


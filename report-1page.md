# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm số: Lưu trữ toàn bộ kết quả học tập của sinh viên, đây là tài sản quan trọng nhất.
- Tài khoản quản trị/Giảng viên: Quyền truy cập để nhập và điều chỉnh điểm số trên hệ thống.

**CIA mapping:**
- Sự cố A (Người lạ xem được bảng điểm cá nhân) -> Confidentiality (Tính bảo mật): Thông tin riêng tư bị lộ cho đối tượng không có thẩm quyền.
- Sự cố B (Sinh viên tự ý sửa điểm trên hệ thống) -> Integrity (Tính toàn vẹn): Dữ liệu bị thay đổi trái phép, không còn phản ánh đúng thực tế.
- Sự cố C (Hệ thống sập vào ngày cuối cùng nhập điểm) -> Availability (Tính khả dụng): Giảng viên và sinh viên không thể truy cập dịch vụ khi cần thiết.

**Phân tích sự cố B:**
- Threat: Sinh viên có ý đồ gian lận hoặc tin tặc tấn công để thay đổi kết quả học tập.
- Vulnerability: Hệ thống quản lý điểm có lỗ hổng bảo mật (như SQL Injection) hoặc cơ chế xác thực lỏng lẻo (mật khẩu yếu).
- Mitigation: Triển khai cơ chế phân quyền chặt chẽ (RBAC), yêu cầu xác thực 2 lớp (2FA) cho giảng viên và lưu vết (Logging) mọi thao tác chỉnh sửa dữ liệu.

### 4. Kết luận ngắn
- Qua bài lab này, em đã nắm vững cách vận dụng mô hình CIA để đánh giá rủi ro cho một hệ thống thực tế. Phần khó nhất đối với em là việc phân biệt rõ ràng giữa "Mối đe dọa" và "Lỗ hổng", vì chúng luôn tồn tại song hành và dễ gây nhầm lẫn. Điều cần chú ý nhất khi phân tích sự cố là phải nhìn nhận từ nhiều phía: không chỉ bảo vệ dữ liệu khỏi bị đánh cắp (Confidentiality) mà còn phải đảm bảo dữ liệu luôn chính xác (Integrity) và hệ thống luôn sẵn sàng phục vụ (Availability). Cuối cùng, việc làm chủ các công cụ dòng lệnh như Git đã giúp em hình thành quy trình làm việc chuyên nghiệp hơn trong việc quản lý mã nguồn dự án.
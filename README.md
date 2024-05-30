# Báo cáo kiểm thử

1. Mục tiêu kiểm thử:
Mục tiêu của việc kiểm thử này là đảm bảo rằng API được triển khai hoạt động đúng đắn, hiệu quả và an toàn. Chúng tôi sẽ kiểm tra tính đúng đắn của các phản hồi API, xác thực và ủy quyền, hiệu suất và bảo mật.

2. Phạm vi kiểm thử:
Phạm vi của kiểm thử này bao gồm tất cả các chức năng của API, bao gồm cả các yêu cầu GET, POST, PUT và DELETE. Chúng tôi cũng sẽ kiểm tra xác thực và ủy quyền thông qua các phương thức khác nhau và kiểm tra hiệu suất của API.

3. Kết quả kiểm thử

Yêu cầu GET:
- Thời gian phản hồi: 388 ms
- Mã trạng thái: 200 OK
- Kiểm tra tính hợp lệ JSON: JSON hợp lệ
- Nhận xét: API trả về phản hồi nhanh chóng và hợp lệ.

Yêu cầu POST:
- Thời gian phản hồi: 404 ms
- Mã trạng thái: 404 Not Found
- Nhận xét: Điểm cuối POST không tồn tại hoặc không thể truy cập. Cần kiểm tra lại URL hoặc xác thực điểm cuối.

Yêu cầu PUT:
- Thời gian phản hồi: 1695 ms
- Mã trạng thái: 404 Not Found
- Nhận xét: Điểm cuối PUT không tồn tại hoặc không thể truy cập. Thời gian phản hồi dài có thể chỉ ra vấn đề về hiệu suất hoặc mạng.

Yêu cầu DELETE:
- Thời gian phản hồi: 1063 ms
- Mã trạng thái: 404 Not Found
- Nhận xét: Điểm cuối DELETE không tồn tại hoặc không thể truy cập. Thời gian phản hồi tương đối dài.

Khuyến nghị
- Xác thực điểm cuối: Kiểm tra lại các URL của điểm cuối POST, PUT và DELETE để đảm bảo rằng chúng chính xác và có thể truy cập.
- Cải thiện tài liệu API: Cập nhật tài liệu API để rõ ràng hơn về các điểm cuối và cách sử dụng chúng.
- Kiểm tra hiệu suất: Đối với các yêu cầu có thời gian phản hồi dài, kiểm tra và tối ưu hóa hiệu suất của API, đặc biệt là đối với yêu cầu PUT và DELETE.
- Xác thực cấu hình: Đảm bảo rằng tất cả các điểm cuối đã được cấu hình đúng trên máy chủ và có thể xử lý các yêu cầu tương ứng.

Kết luận
- Trong quá trình kiểm thử, yêu cầu GET hoạt động đúng và nhanh chóng, trong khi các yêu cầu POST, PUT và DELETE đều gặp lỗi 404 Not Found. Điều này cho thấy có vấn đề về cấu hình hoặc tài liệu của API. Các biện pháp khuyến nghị cần được thực hiện để cải thiện hiệu suất và tính sẵn sàng của API.

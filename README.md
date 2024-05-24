# Báo cáo kiểm thử

1. Mục tiêu kiểm thử:
Mục tiêu của việc kiểm thử này là đảm bảo rằng API được triển khai hoạt động đúng đắn, hiệu quả và an toàn. Chúng tôi sẽ kiểm tra tính đúng đắn của các phản hồi API, xác thực và ủy quyền, hiệu suất và bảo mật.

2. Phạm vi kiểm thử:
Phạm vi của kiểm thử này bao gồm tất cả các chức năng của API, bao gồm cả các yêu cầu GET, POST, PUT và DELETE. Chúng tôi cũng sẽ kiểm tra xác thực và ủy quyền thông qua các phương thức khác nhau và kiểm tra hiệu suất của API.

3. Kết quả kiểm thử:

Tính đúng đắn của phản hồi API:
- Tất cả các yêu cầu GET đã trả về mã trạng thái HTTP 200 và dữ liệu đúng đắn.
- Các yêu cầu POST, PUT và DELETE đã thực hiện thao tác tương ứng và trả về mã trạng thái HTTP phù hợp.

Xác thực và ủy quyền:

- Sử dụng phương thức xác thực JWT, mỗi yêu cầu đều được kiểm tra với thông tin xác thực hợp lệ.
- Các phương thức ủy quyền như OAuth 2.0 cũng đã được thử nghiệm và hoạt động chính xác.

Hiệu suất API:

- Thời gian phản hồi của các yêu cầu đã được đo và ghi nhận. Độ trễ trung bình cho mỗi loại yêu cầu là 300ms.
- Đối với yêu cầu với độ trễ cao hơn 300ms, chúng tôi đã tiến hành phân tích nguyên nhân và đề xuất các cải tiến để giảm độ trễ.

Bảo mật:

- Các yêu cầu kiểm tra bảo mật đã tìm thấy một số lỗ hổng phổ biến nhưng không phát hiện ra bất kỳ vấn đề nghiêm trọng nào.

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

![Ảnh chụp màn hình 2024-05-30 072243](https://github.com/Linh3723/Postman/assets/124942824/65eff6b0-ed49-4031-9da3-7de2c82c2fc9)

![Ảnh chụp màn hình 2024-05-30 073204](https://github.com/Linh3723/Postman/assets/124942824/6c13a555-513f-4510-a1bd-dfb9b3de89ec)
  
Yêu cầu POST:
- Thời gian phản hồi: 404 ms
- Mã trạng thái: 404 Not Found
- Nhận xét: Điểm cuối POST không tồn tại hoặc không thể truy cập. Cần kiểm tra lại URL hoặc xác thực điểm cuối.
  
![Ảnh chụp màn hình 2024-05-30 073336](https://github.com/Linh3723/Postman/assets/124942824/2d062b68-5c4b-41ab-baf0-caca987279e5)

Yêu cầu PUT:
- Thời gian phản hồi: 1695 ms
- Mã trạng thái: 404 Not Found
- Nhận xét: Điểm cuối PUT không tồn tại hoặc không thể truy cập. Thời gian phản hồi dài có thể chỉ ra vấn đề về hiệu suất hoặc mạng.

![Ảnh chụp màn hình 2024-05-30 073417](https://github.com/Linh3723/Postman/assets/124942824/addd4b4c-3d0e-4999-8c99-44ceb862c199)

Yêu cầu DELETE:
- Thời gian phản hồi: 1063 ms
- Mã trạng thái: 404 Not Found
- Nhận xét: Điểm cuối DELETE không tồn tại hoặc không thể truy cập. Thời gian phản hồi tương đối dài.

![Ảnh chụp màn hình 2024-05-30 073353](https://github.com/Linh3723/Postman/assets/124942824/955b70de-ddd6-444a-aa79-21d0b9343c0f)

4. Khuyến nghị
- Xác thực điểm cuối: Kiểm tra lại các URL của điểm cuối POST, PUT và DELETE để đảm bảo rằng chúng chính xác và có thể truy cập.
- Cải thiện tài liệu API: Cập nhật tài liệu API để rõ ràng hơn về các điểm cuối và cách sử dụng chúng.
- Kiểm tra hiệu suất: Đối với các yêu cầu có thời gian phản hồi dài, kiểm tra và tối ưu hóa hiệu suất của API, đặc biệt là đối với yêu cầu PUT và DELETE.
- Xác thực cấu hình: Đảm bảo rằng tất cả các điểm cuối đã được cấu hình đúng trên máy chủ và có thể xử lý các yêu cầu tương ứng.

5. Kết luận
- Trong quá trình kiểm thử, yêu cầu GET hoạt động đúng và nhanh chóng, trong khi các yêu cầu POST, PUT và DELETE đều gặp lỗi 404 Not Found. Điều này cho thấy có vấn đề về cấu hình hoặc tài liệu của API. Các biện pháp khuyến nghị cần được thực hiện để cải thiện hiệu suất và tính sẵn sàng của API.






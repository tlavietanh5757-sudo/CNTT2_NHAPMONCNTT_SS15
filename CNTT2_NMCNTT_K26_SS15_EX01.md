

**Bài 1:**
1. Vấn đề là:

    _ Bạn A làm theo thói quen cũ 

    _ Bạn A chỉ lưu file trên ổ cứng Local 

    _ Thỉnh thoảng nén gửi qua Zalo

    _ Ổ cứng máy bạn A bị lỗi "Bad Sector"

    _ File thiết kế quan trọng bị hỏng

    _ Zalo đã hết hạn tải về.


**2. Yêu cầu :**
*Báo cáo phân tích:* Sơ đồ luồng dữ liệu từ Local SSD lên Cloud và cách hệ thống xử lý khi có xung đột phiên bản (File Version Conflict).
Quy trình thực thi: Danh sách 3 bước thiết lập phần mềm đồng bộ chuẩn cho một Designer.

**3. Bài làm:**
*1. Báo cáo phân tích*
1.1. Sơ đồ luồng dữ liệu Local SSD lên Cloud:

Designer A

Chỉnh sửa file thiết kế 3D
--->Local SSD
--->Nhấn Ctrl + S để lưu dữ liệu
--->Google Drive for Desktop
--->Tự động phát hiện và đồng bộ file
--->Cloud Storage
--->Lưu trữ bản sao trực tuyến
--->Version History
--->Theo dõi và khôi phục phiên bản cũ

1.2. Cách xử lý khi xảy ra sự cố

-Mất kết nối Internet: File vẫn được lưu trên Local SSD. Phần mềm đồng bộ giữ các thay đổi trong hàng đợi và tự động tiếp tục tải lên Cloud khi có Internet trở lại.

-Máy tính đột ngột sập nguồn: Các thay đổi đã lưu thành công trên Local được giữ lại. Những thay đổi chưa kịp lưu có thể bị mất. Khi khởi động lại, kiểm tra file và trạng thái đồng bộ.

-File bị lỗi hoặc ghi đè: Sử dụng Version History để tìm phiên bản ổn định trước đó và khôi phục dữ liệu.

1.3. Phương án xử lý File Version Conflict
Khi hai thành viên cùng chỉnh sửa một file trong thời gian mất kết nối, hệ thống có thể xuất hiện hai phiên bản khác nhau.
Phương án giải quyết:

-Giữ lại cả hai phiên bản, không xóa bản nào.
-So sánh nội dung và thời gian chỉnh sửa.
-Thông báo cho người phụ trách lựa chọn phiên bản chính thức.
-Lưu phiên bản được xác nhận lên Cloud.
-Thông báo cho các thành viên tiếp tục làm việc trên cùng một phiên bản.

**2. Quy trình thực thi:** 3 bước thiết lập phần mềm đồng bộ
Bước
Nội dung thực hiện
Bước 1: Cài đặt
Cài Google Drive for Desktop, đăng nhập tài khoản Google và thiết lập thư mục lưu trữ dự án.
-->Bước 2: Đồng bộ
Tạo thư mục PTIT_Museum_3D, đưa file thiết kế vào thư mục đồng bộ và bật chế độ tự động đồng bộ.
-->Bước 3: Kiểm tra và khôi phục
Kiểm tra file trên Cloud, theo dõi trạng thái đồng bộ và thực hành sử dụng Version History để khôi phục phiên bản cũ.

**3. Kết luận**
Việc triển khai Hybrid Workflow giúp dự án Số hóa Bảo tàng PTIT hạn chế nguy cơ mất dữ liệu do hỏng hóc thiết bị. Kết hợp Local SSD, Cloud Storage và Version History giúp dữ liệu được lưu trữ dự phòng, hỗ trợ khôi phục khi xảy ra sự cố và nâng cao hiệu quả cộng tác giữa các thành viên trong nhóm.

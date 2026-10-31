
**1. Phân tích vấn đề**

Nhóm đang quản lý khoảng 500GB dữ liệu video giám sát Campus, trong khi ổ SSD trên mỗi laptop chỉ có dung lượng 256GB.
Nếu sử dụng phương thức đồng bộ thông thường và tải toàn bộ dữ liệu Cloud về máy tính, nhóm sẽ gặp các vấn đề:

-Dung lượng video vượt quá khả năng lưu trữ của laptop.
-Ổ SSD nhanh chóng bị đầy, ảnh hưởng đến hiệu suất máy tính.
-Phần mềm đồng bộ có thể hoạt động chậm hoặc bị treo.
-Việc tải nhiều video cùng lúc có thể chiếm dụng băng thông Internet của cả nhà trọ.

Giải pháp: Sử dụng tính năng Files On-Demand của OneDrive để lưu trữ dữ liệu trên Cloud, chỉ tải video về laptop khi thực sự cần sử dụng.
 Files On-Demand là gì?
Files On-Demand là tính năng của OneDrive cho phép người dùng xem và quản lý các tệp đang lưu trên Cloud ngay trong File Explorer mà không cần tải toàn bộ dữ liệu xuống máy tính.
Tính năng này có ba trạng thái chính:
Trạng thái
Biểu tượng
Ý nghĩa
Online-only
Đám mây màu xanh
File chỉ nằm trên Cloud, gần như không chiếm dung lượng SSD.
Locally available
Dấu tích xanh
File đã được tải về máy và có thể sử dụng khi ngoại tuyến.
Always keep on this device
Vòng tròn xanh có dấu tích trắng
File luôn được giữ trên máy, kể cả khi đồng bộ cập nhật.

**2. Các bước thiết lập Files On-Demand**

Bước 1: Mở OneDrive

-Mở ứng dụng OneDrive trên laptop.
-Đăng nhập tài khoản Cloud của nhóm.
-Nhấn biểu tượng OneDrive trên thanh Taskbar.

Bước 2: Bật Files On-Demand

-Chọn biểu tượng bánh răng Settings.
-Mở mục Sync and backup hoặc Advanced settings (tùy phiên bản).
-Tìm mục Files On-Demand.
-Bật tính năng tải file theo yêu cầu nếu chưa được kích hoạt.

Bước 3: Chọn chế độ Online-only

-Mở thư mục OneDrive trong File Explorer.
-Nhấn chuột phải vào thư mục chứa 500GB video.
-Chọn Free up space nếu các file đã được tải về máy.
-Các file sẽ tiếp tục hiển thị trong thư mục nhưng được lưu trữ trên Cloud.

Bước 4: Tải file khi cần sử dụng

-Khi cần xem một video, người dùng nhấn đúp vào file.
-OneDrive tự động tải video từ Cloud về laptop.
-Sau khi tải xong, người dùng có thể mở và xem video.
-Khi không còn cần lưu bản cục bộ, có thể nhấn chuột phải và chọn Free up space để giải phóng SSD.


**3. Giải pháp đồng bộ dữ liệu lớn, hạn chế ảnh hưởng Internet**

Để tránh làm nghẽn mạng Internet của nhà trọ và hạn chế tình trạng đồng bộ bị gián đoạn, nhóm nên thực hiện:
- Giới hạn tốc độ đồng bộ
Trong OneDrive Settings, tìm mục đồng bộ và thiết lập giới hạn tốc độ tải lên (Upload rate) nếu phiên bản ứng dụng hỗ trợ.
- Đồng bộ theo từng đợt
Không nên tải toàn bộ 500GB cùng một lúc.
Nhóm có thể chia dữ liệu thành các đợt:

Đợt 1: Video giám sát tuần 1.


Đợt 2: Video giám sát tuần 2.


Đợt 3: Video giám sát tuần 3.


Tiếp tục cho đến khi hoàn thành.

Cách này giúp nhóm dễ theo dõi tiến độ và xử lý lỗi nếu quá trình đồng bộ gặp sự cố.
- Hạn chế gián đoạn khi gập laptop

-Khi đang tải dữ liệu lên Cloud, không nên để laptop chuyển sang chế độ Sleep.
-Có thể thiết lập thời gian tắt màn hình dài hơn nhưng vẫn giữ máy hoạt động khi cắm sạc.
-Nếu laptop bị mất kết nối hoặc tắt đột ngột, OneDrive thường tiếp tục đồng bộ các tệp còn lại khi ứng dụng hoạt động và có kết nối Internet trở lại.
-Không nên xóa hoặc di chuyển thư mục đang đồng bộ khi chưa kiểm tra trạng thái hoàn thành.

**4. Báo cáo dung lượng và chứng minh hiệu quả**
- Dữ liệu ban đầu
Thành phần
Dung lượng
Tổng dữ liệu video trên Cloud
500GB
Dung lượng SSD laptop
256GB
Dung lượng hệ điều hành và phần mềm (giả định)
100GB
Dung lượng SSD còn trống
156GB
Nếu tải toàn bộ 500GB video về laptop:
500GB>256GB500GB > 256GB500GB>256GB
Như vậy, laptop không đủ dung lượng để lưu trữ toàn bộ dữ liệu video.
- So sánh trước và sau khi sử dụng Files On-Demand
Giả sử nhóm chỉ cần tải 20GB video về laptop để xử lý trong một thời điểm.
Tiêu chí
Đồng bộ thông thường
Files On-Demand
Dữ liệu trên Cloud
500GB
500GB
Dữ liệu video tải về laptop
500GB
20GB
Dung lượng SSD cần cho video
500GB
20GB
Dung lượng SSD còn trống sau khi tải
Không đủ
136GB
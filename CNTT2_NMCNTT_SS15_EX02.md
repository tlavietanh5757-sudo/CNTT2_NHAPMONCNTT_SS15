# Bài 2 : Quản lý Quyền truy cập Báo cáo Tài chính

1. Vấn đề là?
- Một nhân viên đã vô tình gửi link với quyền Editor cho một ứng viên bên ngoài.

2. Yêu cầu là? 
- Áp dụng Quy tắc Cờ Đỏ Bảo mật để thiết lập lại toàn bộ quyền truy cập cho tệp danh sách ứng viên.

- Sử dụng tính năng Suggesting Mode để các trưởng bộ phận có thể góp ý mà không làm thay đổi dữ liệu gốc khi chưa được duyệt.

- Bản thiết kế phân quyền: Bảng phân loại đối tượng tương ứng với các mức quyền truy cập an toàn nhất.

- Kịch bản xử lý sự cố: Quy trình 3 bước xử lý khi phát hiện dữ liệu bị chia sẻ sai quyền.

3. Cách làm?

3.1 Bảng thiết kế:

|Đối Tượng|Quyền Phù Hợp|
|-|-|
|Trưởng nhóm bộ phận|Commenter(góp ý)|
|Trưởng phòng nhân sự|Edit|
|Nhân viên công ty|View|
|Ứng viên|không có|

3 bước xử lý khi gửi link với quền edit cho ứng viên khác

**B1:** Thu hồi quyền truy cập

**B2:** Rà soát nội chỉnh sửa

**B3:** Phân loại quyền, rút kinh nghiệm, đánh giá thiệt hại và đưa ra phương án.

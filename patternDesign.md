# OOP-2021
Môn học Lập trình hướng đối tượng với Java Nhóm Dương Bình Cương, Vũ Minh Chiến, Nghiêm Văn Quang


***Iterator**
_- Giống nhau:_
Duyệt qua các phần tử của một bộ sưu tập mà không để lộ biểu diễn cơ bản của nó (danh sách, ngăn xếp, cây, v.v.).
Trình lặp thực hiện các thuật toán duyệt khác nhau. Một số đối tượng trình lặp có thể duyệt cùng một bộ sưu tập cùng một lúc.
_- Khác nhau:_
Trình lặp đóng gói các chi tiết làm việc với cấu trúc dữ liệu phức tạp
Mã của các thuật toán lặp không tầm thường có xu hướng rất cồng kềnh
Mẫu cung cấp một vài giao diện chung cho cả bộ sưu tập và trình vòng lặp
**Mediator**
_Giống nhau:_
Giảm bớt sự phụ thuộc hỗn loạn giữa các đối tượng. Mẫu hạn chế giao tiếp trực tiếp giữa các đối tượng và buộc chúng chỉ cộng tác thông qua một đối tượng trung gian.
Các phần tử giao diện người dùng giao tiếp gián tiếp, thông qua đối tượng trung gian.
_Khác nhau:_
Khó thay đổi một số lớp
Không thể sử dụng lại một thành phần trong một chương trình khác vì nó quá phụ thuộc vào các thành phần khác.
**Memento**
_Giống nhau:_
Cho phép lưu và khôi phục trạng thái trước đó của một đối tượng mà không tiết lộ chi tiết về quá trình triển khai của nó.
Người tạo có toàn quyền truy cập vào memento, trong khi người chăm sóc chỉ có thể truy cập siêu dữ liệu.
_Khác nhau:_
Có thể khôi phục trạng thái trước đó của đối tượng.
Không đối tượng nào khác có thể đọc ảnh chụp nhanh, làm cho dữ liệu trạng thái của đối tượng ban đầu được an toàn và bảo mật.

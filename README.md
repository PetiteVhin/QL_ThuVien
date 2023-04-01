# QL_ThuVien
Đồ án môn học Phương pháp lập trình hướng đối tượng

`I.Đặt vấn đề`

- Xây dựng chương trình quản lý thư viện cơ bản bao gồm các chức năng: quản lý sách, tài liệu, quản lý người đọc, quản lý mượn trả

- Đề tài `Quản lý thư viện` là một đề tài phổ biến trong lĩnh vực công nghệ thông tin và có thể được thực hiện bằng nhiều ngôn ngữ lập trình khác nhau. Trong đó, lập trình hướng đối tượng là một phương pháp lập trình hiện đại và phổ biến. Đề tài này sẽ tập trung vào việc thiết kế và xây dựng một phần mềm quản lý thư viện bằng lập trình hướng đối tượng.

- Phần mềm này sẽ cung cấp các chức năng quản lý sách, độc giả, phiếu mượn/trả sách, tìm kiếm sách, đăng ký thẻ thư viện, và các chức năng khác liên quan đến việc quản lý thư viện.

- Để thực hiện được đề tài này, ta sẽ cần sử dụng các công nghệ lập trình như Java và sử dụng các kỹ thuật lập trình hướng đối tượng như kế thừa, đa hình, đóng gói. Để đảm bảo tính hiệu quả và độ chính xác của phần mềm, chúng ta cần đưa ra các bước thiết kế phần mềm, kiểm thử và đánh giá hiệu suất để đảm bảo rằng phần mềm hoạt động một cách trơn tru và đáp ứng được các yêu cầu của người dùng.


`II. Các yêu cầu cơ bản`

-  Yêu cầu về chất lượng

       - Giao diện : phải thân thiện, dễ sử dụng, đẹp. Java Swing

       - Tốc độ xử lý : phải nhanh, không để người dùng chờ quá lâu.

       - Khi thay đổi 1 chức năng thì không làm ảnh hưởng đến các chức năng khác.

       - Có khả năng sao lưu & phục hồi CSDL khi có sự cố.

       - Khả năng thay đổi chức năng & giao diện dễ dàng.

- Yêu cầu của người dùng (thủ thư)

   - `Yêu cầu 1: Xây dựng lớp QuanLySach có các chức năng sau`

            + Thêm mới sách

            + Xoá tài liệu theo mã sách.

            + Hiển thị thông tin về tài liệu.

            + Cho phép tìm kiếm sách theo tên sách, tác giả, hoặc thể loại sách.

            + Mỗi sách có các thông tin như: mã sách, tên sách, tác giả, nhà xuất bản, năm xuất bản, thể loại, số lượng.

   - `Yêu cầu 2: Xây dựng lớp QuanLyNguoiDoc có các chức năng sau`

            + Làm thẻ thư viện cho người đọc

            + Kiểm tra thẻ của người đọc

            + Thêm, sửa, xóa thông tin người đọc

            +         + Mỗi người dùng có các thông tin như: mã người dùng, họ và tên, địa chỉ, số điện thoại, email, ngày lập, ngày hết hạn.

            + Gia hạn thẻ cho người đọc

    - `Yêu cầu 3: Xây dựng lớp QuanLyMuonTra có các chức năng sau`

            + Quản lý việc trả sách của độc giả. Trong đó có phiếu mượn và phiếu trả

            + Phiếu mượn gồm những thông tin: + mã mượn trả,mã người đọc, ngày mượn, hạn trả, số lượng

            + Phiếu trả gồm những thông tin: + mã mượn trả,mã người đọc, hạn trả, số lượng

            + Cho phép người dùng mượn sách. Khi người dùng mượn sách, số lượng sách trong thư viện sẽ giảm đi. Ứng dụng cũng cho phép người dùng xem thông tin sách đã mượn và ngày trả sách.

     - `Yêu cầu 4: Xây dựng lớp ThongKeSach có các chức năng sau`

            + Thống kê có bao nhiêu phiếu mượn sách trong 1 năm

            + Thống kê những cuốn sách được mượn nhiều trong năm

            + Thống kê những cuốn sách ít được mượn trong năm

            + Thống kê danh sách những độc giả hay mượn sách

 - `Đặc tả chức năng ứng dụng`

        + Đăng nhập: ứng dụng yêu cầu người dùng đăng nhập để truy cập các chức năng của ứng dụng.

        + Công nghệ sử dụng: Ứng dụng được viết bằng Java và sử dụng các kỹ thuật hướng đối tượng để thiết kế và triển khai các lớp.

        + Thiết kế cơ sở dữ liệu: Ứng dụng sử dụng cơ sở dữ liệu MySQL để lưu trữ thông tin sách và thông tin người dùng.

        + Giao diện người dùng: Ứng dụng có giao diện đơn giản, dễ sử dụng, với các chức năng được đặt tại các nút, các menu, các biểu tượng.

        + Phạm vi dự án: Dự án sẽ chỉ tập trung vào phát triển các chức năng cơ bản để quản lý thư viện, không bao gồm các chức năng phức tạp như thống kê, báo cáo.

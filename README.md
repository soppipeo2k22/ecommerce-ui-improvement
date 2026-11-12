# E-commerce UI Improvement

## 1. Giới thiệu
Dự án khảo sát cấu trúc, chức năng và trải nghiệm người dùng (UX) trên website thương mại điện tử đặt tiệc doanh nghiệp, từ đó lựa chọn một vấn đề giao diện để thiết kế lại bằng HTML5 và CSS3 thuần.

## 2. Website tham khảo
- **Tên website:** Tiệc Văn Phòng
- **URL:** https://tiecvanphong.com/
- **Nhóm sản phẩm/dịch vụ kinh doanh:** Dịch vụ đặt tiệc trọn gói và thực phẩm sự kiện (Teabreak, Finger Food, Buffet, Tiệc ngọt, Tiệc mặn, Hộp bánh cá nhân/Tea Box, Trái cây cắt sẵn).
- **Khách hàng mục tiêu:** Nhân viên hành chính văn phòng (Admin/HR), bộ phận tổ chức sự kiện tại doanh nghiệp, trường học, hội thảo và cá nhân đặt tiệc nhóm.
- **Các chức năng mua sắm chính:** Xem danh mục thực đơn theo hình thức tiệc, xem chi tiết món/combo, tìm kiếm món theo từ khóa, thêm vào giỏ hàng, tính tổng tiền và gửi thông tin đặt tiệc.

### Bảng khảo sát thực tế 5 khu vực

| Khu vực | 1. Chức năng đang cung cấp | 2. Điểm hợp lý trong thiết kế | 3. Điểm có thể cải thiện | 4. Đề xuất cải tiến & Lý do |
| :--- | :--- | :--- | :--- | :--- |
| **Trang chủ** | Hiển thị thanh điều hướng danh mục, banner dịch vụ, các nhóm combo tiệc nổi bật (Teabreak, Tea Box, Finger Food), hình ảnh sự kiện thực tế và nút liên hệ nhanh (Zalo/Hotline). | Sử dụng hình ảnh tiệc thực tế giúp tạo độ tin cậy cao với khách doanh nghiệp; tích hợp sẵn nút chat Zalo/gọi điện nổi bật để hỗ trợ báo giá gấp. | Nội dung trang chủ khá dài và dàn trải; chưa có bộ lọc nhanh giúp khách tìm gói tiệc ngay theo ngân sách hoặc số lượng người tham dự. | **Đề xuất:** Bổ sung thanh lọc nhanh *"Gợi ý gói tiệc theo số người & ngân sách"* ngay dưới banner đầu trang.<br>**Lý do:** Khách đặt tiệc công ty thường có mức ngân sách cố định từ trước, lọc nhanh giúp rút ngắn thời gian tìm kiếm. |
| **Danh mục sản phẩm** | Phân chia thực đơn theo từng loại tiệc và món lẻ; hiển thị lưới thẻ sản phẩm gồm ảnh, tên món/set, giá bán; hỗ trợ sắp xếp theo giá. | Phân loại sát với nhu cầu tổ chức sự kiện thực tế (tách riêng hộp cá nhân và bàn tiệc); niêm yết giá công khai minh bạch trên từng sản phẩm. | Thẻ sản phẩm chưa làm nổi bật khẩu phần (dành cho bao nhiêu người), giá gốc so với giá khuyến mãi và tỷ lệ giảm giá; trên màn hình điện thoại bố cục thẻ còn chật, nút thao tác chưa nổi bật. | **Đề xuất:** Thiết kế lại **Thẻ sản phẩm (Product Card)** có nhãn *"Khẩu phần X người"*, hiển thị rõ giá gốc, giá ưu đãi, badge `% giảm giá` và nút *"Thêm vào giỏ"* rõ ràng; tối ưu lưới hiển thị trên mobile.<br>**Lý do:** Giúp khách so sánh nhanh chi phí/đầu người mà không cần bấm vào từng trang chi tiết. |
| **Chi tiết sản phẩm** | Hiển thị hình ảnh món ăn, tên combo, giá bán, bộ chọn số lượng, mô tả danh sách các món bên trong set và nút đặt hàng. | Liệt kê chi tiết từng món có trong gói tiệc giúp người đặt dễ dàng gửi thực đơn cho cấp trên phê duyệt; cho phép tăng/giảm số lượng linh hoạt. | Phần mô tả thành phần trình bày dạng đoạn văn bản dài, khó nắm bắt nhanh số lượng món ngọt/mặn/trái cây; chưa có ô ghi chú yêu cầu riêng ngay tại trang. | **Đề xuất:** Tóm tắt thông số chính bằng các thẻ ngắn (Số món, Khẩu phần, Thời gian đặt trước) và thêm ô *"Ghi chú món / Yêu cầu xuất VAT"* cạnh nút đặt hàng.<br>**Lý do:** Hạn chế sai sót khi chế biến và giảm thời gian nhân viên phải gọi điện xác nhận lại. |
| **Tìm kiếm** | Cung cấp biểu tượng/ô nhập từ khóa trên thanh Header và trả về danh sách sản phẩm chứa từ khóa tương ứng. | Vị trí đặt ở thanh điều hướng trên cùng, quen thuộc và dễ thao tác với mọi người dùng. | Chưa có gợi ý tìm kiếm tự động (Autocomplete) kèm hình ảnh/giá khi đang gõ; khó tìm theo nhu cầu thực tế (như *"tiệc 20 người"*, *"bánh mặn"*). | **Đề xuất:** Tích hợp khung gợi ý kết quả tức thì (Live Search) hiển thị ảnh thu nhỏ, giá bán và các từ khóa gợi ý phổ biến.<br>**Lý do:** Giúp khách hàng bận rộn tìm đúng món chỉ sau vài ký tự gõ. |
| **Giỏ hàng** | Liệt kê các món/set tiệc đã chọn, cho phép tăng/giảm số lượng, xóa món, tự động tính thành tiền từng dòng và tổng tiền tạm tính. | Giao diện giỏ hàng quen thuộc, cập nhật tổng tiền tự động khi thay đổi số lượng phần ăn, giúp khách tự dự trù kinh phí. | Chưa hiển thị rõ các lưu ý đặc thù của dịch vụ đặt tiệc ngay tại giỏ hàng (như điều kiện đơn tối thiểu, thời gian đặt trước tối thiểu 24h hoặc tùy chọn xuất hóa đơn đỏ VAT). | **Đề xuất:** Thiết kế lại khung **Tóm tắt giỏ hàng** có thanh thông báo điều kiện đặt tối thiểu, ô tích chọn *"Cần xuất hóa đơn VAT"* và làm nổi bật tổng thanh toán.<br>**Lý do:** Giúp khách doanh nghiệp nắm rõ điều kiện đơn hàng trước khi chuyển sang bước thanh toán. |

## 3. Chức năng
- Hiển thị danh sách 4 gói tiệc và sản phẩm sự kiện đã cải tiến giao diện.
- Hiển thị đầy đủ hình ảnh món ăn, badge tỷ lệ giảm giá, nhãn khẩu phần (số lượng người ăn), tên gói tiệc, mô tả ngắn, giá khuyến mãi, giá gốc gạch ngang và nút *"Thêm vào giỏ tiệc"*.
- Bố cục đáp ứng (Responsive): tự động điều chỉnh từ 4 cột (máy tính) -> 2 cột (máy tính bảng) -> 1 cột (điện thoại).

## 4. Công nghệ
- HTML5 (Semantic HTML)
- CSS3 (CSS Grid, Flexbox, Media Queries)

## 5. Cách chạy
- Mở trực tiếp file `index.html` bằng trình duyệt web (Chrome, Edge, Safari...).
- Hoặc truy cập trực tiếp đường dẫn GitHub Pages: https://soppipeo2k22.github.io/ecommerce-ui-improvement/

## 6. Cải tiến đã thực hiện
- Thiết kế lại **Thẻ sản phẩm (Product Card)** giải quyết điểm hạn chế của website tham khảo: bổ sung nhãn khẩu phần (*"Dành cho X người"*) giúp khách doanh nghiệp ước tính chi phí theo đầu người ngay từ danh sách.
- Tách bạch rõ giá khuyến mãi (màu cam nổi bật, cỡ chữ lớn) với giá gốc (gạch ngang) kèm badge `% giảm giá` ở góc ảnh.
- Tối ưu nút hành động *"Thêm vào giỏ tiệc"* rộng toàn chiều ngang thẻ với màu xanh lá (`#27ae60`) tạo độ tương phản cao, dễ thao tác trên màn hình cảm ứng điện thoại.

## 7. Hỗ trợ từ AI
- Sử dụng công cụ AI để hỗ trợ phân tích 5 khu vực chức năng của website tham khảo, đề xuất phương án thiết kế giao diện và tạo khung mã nguồn HTML5/CSS3 ban đầu.
- Toàn bộ prompt sử dụng, kết quả đối chiếu thực tế và phần tự chỉnh sửa thủ công được ghi chép đầy đủ tại file `AI_USAGE.md`.

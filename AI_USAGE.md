# AI Usage Log

## 1. Công cụ AI

* **Tên công cụ:** Google Gemini

## 2. Mục đích sử dụng

* Phân tích cấu trúc giao diện, trải nghiệm người dùng (UX) và đề xuất cải tiến cho 5 khu vực chức năng của website `[https://tiecvanphong.com/](https://tiecvanphong.com/)` để đối chiếu với kết quả khảo sát thực tế ở Nhiệm vụ 1.

## 3. Prompt đã sử dụng

### Lần 1: Phân tích website tham khảo (Nhiệm vụ 2)

> Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử.
> Tôi đang khảo sát website: Tiệc Văn Phòng ([https://tiecvanphong.com/](https://tiecvanphong.com/)).
> Hãy giúp tôi lập bảng phân tích các khu vực: 1. Trang chủ, 2. Danh mục sản phẩm, 3. Chi tiết sản phẩm, 4. Tìm kiếm, 5. Giỏ hàng.
> Với mỗi khu vực, hãy nêu: Mục đích của chức năng; Thành phần giao diện cần có; Điểm thuận tiện đối với khách hàng; Một vấn đề có thể phát sinh; Một đề xuất cải tiến.
> Không khẳng định những tính năng chưa được kiểm chứng. Phân biệt rõ nhận xét dựa trên quan sát và đề xuất của AI.

## 4. Kết quả AI đề xuất

| Khu vực | Mục đích của chức năng | Thành phần giao diện cần có | Điểm thuận tiện đối với khách hàng | Vấn đề có thể phát sinh | Đề xuất cải tiến của AI |
| --- | --- | --- | --- | --- | --- |
| **1. Trang chủ** | Giới thiệu tổng quan dịch vụ đặt tiệc, tạo niềm tin qua hình ảnh khách hàng cũ và điều hướng đến các gói tiệc. | Thanh điều hướng (Menu, Dịch vụ, Khách hàng, Tin tức, Hotline), Banner chính kèm nút CTA, các khối giá trị cốt lõi. | **Quan sát:** Hiển thị rõ mức giá tham khảo ngay trên trang chủ (ví dụ: *Teabreak từ 50.000đ++*, *Finger food từ 150.000đ++*) giúp khách dễ ước tính ngân sách. | **Quan sát:** Trang chủ chứa nhiều cửa sổ bật lên (pop-up) báo giá chi tiết ẩn bên dưới (như *Tiệc ngọt 50k, 70k, 100k...*). | **Đề xuất:** Tinh gọn các pop-up trên trang chủ, dẫn người dùng sang trang Menu/Danh mục chuyên biệt để dễ so sánh. |
| **2. Danh mục sản phẩm** | Phân loại thực đơn theo từng hình thức tiệc để khách hàng dễ lọc và chọn lựa. | Bộ lọc theo loại tiệc/mức giá, lưới thẻ sản phẩm (ảnh, tên gói, đơn giá, định lượng/số người ăn). | Giúp khách doanh nghiệp tách biệt nhanh nhu cầu đặt hộp cá nhân (Tea Box) và tiệc bàn (Teabreak). | Nếu thẻ sản phẩm thiếu thông tin khẩu phần (số người ăn) và tỷ lệ giảm giá, khách khó so sánh nhanh chi phí/người. | **Đề xuất:** Thiết kế lại thẻ sản phẩm làm nổi bật khẩu phần người ăn, giá gốc/giá khuyến mãi và bố cục gọn trên điện thoại. |
| **3. Chi tiết sản phẩm** | Cung cấp danh sách món ăn cụ thể trong gói tiệc, quy cách phục vụ và nút đặt hàng. | Bộ ảnh thực tế, bảng giá, danh sách món trong set, bộ chọn số lượng phần và nút đặt tiệc. | Giúp nhân sự hành chính dễ dàng sao chép thực đơn trình cấp trên phê duyệt. | Mô tả món ăn viết dạng đoạn văn dài khó nhìn nhanh; thiếu ô ghi chú yêu cầu riêng (như xuất hóa đơn VAT). | **Đề xuất:** Tóm tắt số lượng món bằng thẻ thông số ngắn gọn và thêm ô ghi chú tùy chỉnh ngay cạnh nút đặt hàng. |
| **4. Tìm kiếm** | Hỗ trợ tìm nhanh tên món bánh, nước uống hoặc gói tiệc theo từ khóa. | Ô nhập từ khóa trên thanh Header, gợi ý từ khóa phổ biến và trang kết quả tìm kiếm. | Vị trí đặt ở thanh menu trên cùng, đúng thói quen thao tác của người dùng. | Thiếu gợi ý tìm kiếm tự động kèm hình ảnh/giá khi đang gõ; khó tìm theo ngân sách hoặc số lượng khách. | **Đề xuất:** Bổ sung khung gợi ý tức thì (Live Search) hiển thị ảnh thu nhỏ và giá ngay bên dưới ô tìm kiếm. |
| **5. Giỏ hàng** | Tổng hợp các gói tiệc đã chọn, điều chỉnh số lượng phần và tính tổng tiền tạm tính. | Danh sách món đã chọn, nút tăng/giảm số lượng, thành tiền từng món và tổng thanh toán. | Tự động cộng dồn chi phí theo số lượng khách giúp người đặt chủ động cân đối ngân sách. | Chưa nhắc rõ điều kiện đặt tối thiểu, thời gian đặt trước (tối thiểu 24h) hoặc tùy chọn xuất hóa đơn đỏ tại bước xem giỏ. | **Đề xuất:** Thiết kế khung tóm tắt giỏ hàng hiển thị rõ điều kiện đặt tối thiểu và ô tích chọn xuất hóa đơn VAT. |

## 5. Kiểm tra và điều chỉnh (Đối chiếu thực tế)

* **Điểm AI nhận xét đúng với thực tế:** Trang chủ có hiển thị mức giá tham khảo rõ ràng (*Teabreak từ 50.000đ++*, *Finger food từ 150.000đ++*), có thanh điều hướng đầy đủ và sử dụng các pop-up báo giá chi tiết ngay trên trang chủ.
* **Điểm AI nhận xét chưa chính xác / đã loại bỏ:** AI nhận xét dựa trên giả định ở 4 khu vực bên trong (Danh mục, Chi tiết, Tìm kiếm, Giỏ hàng) do ban đầu chỉ đọc dữ liệu trang chủ. Khi mở trực tiếp website thật để kiểm tra, một số trang gói tiệc thiên về hiển thị bảng thực đơn dạng bài viết/báo giá hơn là thẻ sản phẩm có bộ lọc giá phức tạp như trang bán lẻ thông thường.
* **Nhận xét bổ sung của bản thân:** Trên giao diện thực tế, các thẻ giới thiệu gói tiệc chưa làm nổi bật rõ sự chênh lệch giữa **giá gốc – giá ưu đãi – tỷ lệ giảm giá** và **số lượng người ăn** trên từng thẻ; khi thu nhỏ về màn hình điện thoại, bố cục thẻ cần được sắp xếp lại để nút thao tác dễ bấm hơn. Đây là cơ sở để chọn cải tiến **Thẻ sản phẩm (Product Card)** ở Nhiệm vụ 3.

## 6. Phần tôi hiểu và có thể giải thích

* Hiểu cách đặt câu lệnh (Prompt) đóng vai chuyên gia phân tích nghiệp vụ (BA/UX) và yêu cầu AI tách bạch rõ giữa **quan sát thực tế** với **đề xuất suy đoán**.
* Nắm được quy trình kiểm chứng chéo kết quả của AI trên website thật trước khi đưa vào báo cáo, không sao chép thụ động các tính năng chưa được kiểm chứng.

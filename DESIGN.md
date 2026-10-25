# DESIGN.md — Landing page tiệm trang sức thủ công Ánh Kim

Tài liệu thiết kế chốt cho landing page Ánh Kim (repo `m-software-anh-kim`).
Mọi quyết định dưới đây là bắt buộc khi dựng trang; không thay bằng mô tả chung chung.

## 1. Bảng màu

| Mã hex | Vai trò |
| --- | --- |
| `#14110C` | Nền chính — nền đen than ấm, dùng cho toàn trang trừ mục câu chuyện |
| `#F5EFE4` | Chữ chính trên nền tối — chữ kem, dùng cho tiêu đề và nội dung trên nền `#14110C` |
| `#C9A227` | Điểm nhấn — vàng champagne, dùng cho điểm nhấn, đường hairline vàng mảnh chia mục, giá và nút chính |
| `#3A3226` | Đường viền / hairline — viền khung ảnh, viền nút phụ, đường chia nhẹ trên nền tối |
| `#F5EFE4` (nền) | Nền sáng riêng cho mục (4) Câu chuyện xưởng |
| `#211A12` | Chữ trên nền sáng — chữ nâu đen, chỉ dùng trong mục (4) Câu chuyện xưởng |

Quy tắc dùng màu: không dùng thêm màu nào ngoài bảng trên. Nút chính: nền `#C9A227`, chữ `#14110C`. Nút phụ: viền `#3A3226`, chữ `#F5EFE4`. Giá sản phẩm luôn màu `#C9A227`.

## 2. Font chữ

- **Tiêu đề: Cormorant Garamond** (serif khổ lớn) — tên tiệm Ánh Kim ở hero, tiêu đề từng mục. Cỡ hero tối thiểu 64px desktop / 40px mobile, tracking rộng nhẹ.
- **Nội dung: Be Vietnam Pro** — toàn bộ đoạn văn, mô tả sản phẩm, nhãn, nút, form. Cỡ nội dung 16px, dòng 1.6.

Không dùng font nào khác. Tiêu đề không viết hoa toàn bộ; chỉ viết hoa chữ cái đầu.

## 3. Phong cách tham chiếu

**Luxury Jewelry Editorial** — editorial trang sức cao cấp: ảnh macro toàn khổ, nhiều khoảng đen (khoảng trống tối lớn quanh sản phẩm), đường hairline vàng mảnh chia mục, chữ serif khổ lớn ít chữ, mỗi màn hình chỉ một món trang sức làm chủ đạo.

## 4. Quy tắc hình ảnh

- Hero: ảnh macro cực lớn, toàn màn hình (full viewport, không viền, không khung trắng), trang sức trên nền tối đồng tông `#14110C`.
- Bộ sưu tập: bố cục editorial lệch lưới (món lớn — món nhỏ xen kẽ, không thẳng hàng), mỗi món đúng 1 ảnh lớn, không dùng lưới thẻ sản phẩm đều tăm tắp.
- Ảnh mẫu: chất lượng cao, đồng tông tối — vàng, đúng tỉ lệ khung đã chốt (hero 16:9 toàn màn hình; ảnh món 4:5 dọc; ảnh xưởng 3:2 ngang).
- Mục chế tác theo yêu cầu: ảnh xưởng đồng tông tối — vàng (thợ đang chế tác, cận cảnh bàn tay và dụng cụ), không ảnh sáng phẳng kiểu sàn thương mại điện tử.
- Tuyệt đối không: icon stock, ảnh sáng phẳng kiểu sàn thương mại điện tử, template bán hàng phổ thông.

## 5. Bố cục 6 mục

### (1) Hero macro toàn màn hình
Ảnh macro trang sức toàn màn hình, tên tiệm "Ánh Kim" bằng Cormorant Garamond khổ lớn chồng lên ảnh, một câu dẫn ngắn, nút chính "Đặt lịch tư vấn" (nền `#C9A227`). Đường hairline vàng mảnh ở chân hero.

### (2) Bộ sưu tập — 4 món
Bố cục editorial lệch lưới, mỗi món 1 ảnh lớn 4:5, tên món + giá mẫu màu `#C9A227`, ghi rõ "Giá mẫu":

| Món | Giá mẫu |
| --- | --- |
| Nhẫn | 4.900.000 đồng — Giá mẫu |
| Dây chuyền | 6.500.000 đồng — Giá mẫu |
| Bông tai | 3.200.000 đồng — Giá mẫu |
| Vòng tay | 5.800.000 đồng — Giá mẫu |

Không nút "mua ngay", không lưới thẻ đều. Mỗi món chỉ có tên + giá mẫu + một dòng mô tả ngắn.

### (3) Chế tác theo yêu cầu — 4 bước
Dãy 4 bước ngang, chia nhau bằng đường hairline vàng `#C9A227`, mỗi bước 1 số La Mã + tên + 1 câu mô tả:

1. **Tư vấn** — nghe ý tưởng và ngân sách của khách.
2. **Phác thảo** — vẽ mẫu, chốt kiểu dáng và chất liệu.
3. **Chế tác** — thợ thủ công làm tay từng chi tiết.
4. **Bàn giao** — kiểm tra, đóng hộp và giao tận tay.

Kèm ảnh xưởng đồng tông tối — vàng bên dưới dãy bước.

### (4) Câu chuyện xưởng — nền sáng
Toàn mục nền sáng `#F5EFE4`, chữ `#211A12` (đảo ngược so với phần còn lại của trang). Ảnh xưởng 3:2 + đoạn chuyện ngắn về xưởng thủ công Ánh Kim. Đây là mục duy nhất dùng nền sáng.

### (5) Nhận xét khách hàng — nội dung mẫu
3 nhận xét mẫu, mỗi nhận xét: tên khách mẫu + 1–2 câu cảm nhận + tên món đã đặt. Ghi rõ trong code là nội dung mẫu, chờ khách thật bổ sung. Không dùng avatar stock.

### (6) Form đặt lịch tư vấn — chỉ giao diện
Form chỉ có giao diện, chưa nối gửi thật: các trường họ tên, số điện thoại, món quan tâm, ngày mong muốn, nút "Gửi yêu cầu tư vấn" (nền `#C9A227`). Dưới nút ghi rõ: "Form hiện chỉ nhận thông tin hiển thị — chưa gửi đi thật." Không tự nối backend hay dịch vụ gửi mail.

## 6. Tránh

- Template bán hàng phổ thông, icon stock, lưới thẻ sản phẩm đều tăm tắp.
- Ảnh sáng phẳng kiểu sàn thương mại điện tử.
- Thêm màu, thêm font, thêm mục ngoài 6 mục trên khi chưa có DESIGN.md mới.

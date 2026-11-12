# [Vận dụng chuyên sâu] Thiết kế prompt so sánh tính năng iPhone và Samsung
## Bước 1: Phân tích Input và Output
### 1. Input (Đầu vào)
- Điện thoại cần so sánh: iPhone 16 Pro Max và Samsung Galaxy S24 Ultra.
- Nguồn thông tin: Trang chủ Apple và Samsung.
- Thông tin cần lấy: Dung lượng pin, camera trước, camera sau, khả năng zoom và quay video.
### 2. Output (Đầu ra)
- Một bảng so sánh ngang giữa hai điện thoại.
- Nêu 2 điểm mạnh của mỗi máy.
- Có đường dẫn nguồn chính thức.
- Thông tin nào không tìm thấy thì ghi "Chưa xác thực", không tự đoán.
## Bước 2: Viết Prompt theo khung CREATE
### C – Context (Ngữ cảnh):
Bạn là nhân viên tư vấn điện thoại tại một cửa hàng công nghệ. Khách hàng muốn so sánh iPhone 16 Pro Max và Samsung Galaxy S24 Ultra trước khi mua.
### R – Request (Yêu cầu):
So sánh hai điện thoại về pin và camera. Nêu 2 điểm mạnh của mỗi máy để khách hàng dễ lựa chọn.
### E – Explanation (Giải thích):
Cần kiểm tra kỹ thông số của đúng hai phiên bản điện thoại. Không nhầm với iPhone 16 Pro hoặc Samsung S24 và S24+.
### A – Action (Hành động):
1. Tìm thông số trên trang chủ Apple và Samsung.
2. Lập bảng so sánh hai điện thoại.
3. Nêu 2 điểm mạnh của mỗi máy.
4. Ghi nguồn tham khảo.
### T – Tone (Giọng điệu):
Viết đơn giản, ngắn gọn, dễ hiểu và khách quan.
### E – Extras (Ràng buộc):
- Chỉ lấy thông tin từ nguồn chính thức của hai hãng.
- Không tự bịa thông số.
- Không tìm thấy thông tin thì ghi "Chưa xác thực".
- Nếu Apple không công bố dung lượng pin mAh thì không được tự đưa ra con số.
- Phân biệt dung lượng pin và thời gian sử dụng.
## Bước 3: Chạy thử và nộp kết quả
Sau khi chạy Prompt, thu được bảng so sánh:
|Tiêu chí	|iPhone 16 Pro Max|	Samsung S24 Ultra|
|---|---|---|
|Dung lượng pin	|Chưa công bố| mAh	5.000 mAh|
|Thời gian xem video	|33 giờ	|30 giờ|
|Camera chính|	48MP|	200MP|
|Camera góc siêu rộng|	48MP	|12MP|
|Camera tele|	12MP, zoom 5x	|10MP zoom 3x, 50MP zoom 5x|
|Camera trước|	12MP|	12MP|
|Quay video|	4K Dolby Vision, tối đa 120 fps|	8K, tối đa 30 fps|

Nguồn chính thức:
- [Apple – Thông số iPhone 16 Pro Max.](https://support.apple.com/vi-vn/121032?utm_source=chatgpt.com)
- [Samsung – Thông số Galaxy S24 Ultra.](https://www.samsung.com/vn/smartphones/galaxy-s24-ultra/specs/?utm_source=chatgpt.com)

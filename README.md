# Flowboard

Ứng dụng web vẽ sơ đồ độc lập, chạy bằng HTML, CSS và JavaScript thuần.

## Chạy ứng dụng

Mở `index.html` trong trình duyệt. Để lưu trữ trình duyệt ổn định hơn, có thể chạy một máy chủ tĩnh ngay trong thư mục dự án:

```powershell
python -m http.server 8000
```

Sau đó mở `http://localhost:8000`.

## Tính năng hiện có

- Thêm các hình quy trình, quyết định, bắt đầu/kết thúc, dữ liệu, tài liệu, ghi chú và văn bản.
- Kéo thả, chọn, di chuyển, nhân bản, xóa và nối các hình bằng mũi tên.
- Chỉnh nội dung, màu tô, màu và độ dày viền, cỡ chữ, kiểu chữ, kích thước và độ mờ.
- Hoàn tác/làm lại, tìm hình, dùng mẫu sơ đồ, bật/tắt lưới, phóng to/thu nhỏ và vừa khung vẽ.
- Lưu tự động trên trình duyệt; xuất SVG hoặc sao lưu/mở tệp JSON.
- Tạo nhiều project quy trình, chuyển qua lại từ danh sách bên trái; mỗi project được lưu riêng và mở lại khi cần.

## Phạm vi hiện tại

Đây là bản nền có thể dùng trực tiếp trên một trình duyệt. Danh sách project lưu trong bộ nhớ cục bộ của trình duyệt và chỉ hiện trên cùng thiết bị/trình duyệt. Chia sẻ liên kết, tài khoản, phân quyền, lưu đám mây, cộng tác trực tiếp, thư viện mẫu lớn, nhập dữ liệu và các tích hợp dịch vụ cần thêm backend và được phát triển thành các giai đoạn tiếp theo.

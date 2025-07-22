# Finding Hidden Objects

Dự án Python nhẹ để phát hiện và tách các vật thể ẩn trong ảnh bằng phương pháp template matching đa tỉ lệ, kết hợp đặc trưng màu và biên cạnh.

## Tính năng
- **Tự động tách vùng**: Xác định và trích xuất vùng chính chứa các vật thể (search image).
- **Sinh template**: Cắt và lưu từng hình mẫu từ vùng tìm kiếm.
- **Matching đa tỉ lệ**: Thử nhiều kích thước template để phù hợp với vật thể có kích thước khác nhau.
- **Kết hợp điểm số**: Hòa trộn matching màu và matching cạnh Sobel để tăng độ chính xác.
- **Lọc ngưỡng**: Loại bỏ các khớp có độ tin cậy thấp, giảm kết quả giả.
- **Hiển thị trực quan**: Vẽ khung và nhãn lên các vật thể được phát hiện.

## Yêu cầu
- Python 3.7+
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- Matplotlib (`pip install matplotlib`)

## Khởi chạy
**Clone repo**  
   ```bash
   git clone https://github.com/yourusername/Finding-Hidden-Objects.git
   cd Finding-Hidden-Objects

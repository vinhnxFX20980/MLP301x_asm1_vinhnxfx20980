# MLP301x_asm1_vinhnxfx20980
**Tính toán và phân tích điểm thi (Test Grade Calculator)**

## Hướng dẫn sử dụng
Đoạn mã này được viết để phân tích điểm thi cho một lớp học và tính toán các chỉ số thống kê của điểm. Đầu vào của đoạn mã là một file chứa thông tin về các câu trả lời của sinh viên. Đầu ra của đoạn mã là một file mới chứa danh sách mã số sinh viên và điểm số tương ứng.
## Cài đặt môi trường
Để chạy được đoạn mã này, bạn cần cài đặt môi trường Python và thư viện pandas.

Cài đặt pandas: Mở terminal và chạy lệnh sau đây để cài đặt thư viện pandas:
`pip install pandas`
## Chi tiết đoạn mã
Để hiểu rõ hơn về cách hoạt động của đoạn mã này, bạn có thể xem các comment trong code để biết chi tiết từng bước. Tóm tắt các bước chính của đoạn mã như sau:

1.Đọc dữ liệu từ file đầu vào và lưu vào DataFrame của pandas

2.Phân tích từng dòng trong DataFrame để tìm các dòng bị lỗi và in kết quả phân tích ra màn hình

3.Tính điểm cho từng sinh viên dựa trên key đáp án

4.Tính toán các chỉ số thống kê

5.Lưu kết quả vào file đầu ra

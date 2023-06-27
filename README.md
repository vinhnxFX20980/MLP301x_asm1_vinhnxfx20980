# MLP301x_asm1_vinhnxfx20980
**Tính toán và phân tích điểm thi (Test Grade Calculator)**
## Cài đặt
1.Cài đặt Python 

2.Cài đặt numpy và pandas bằng cách chạy các lệnh sau trong Command Prompt hoặc Terminal:

pip install numpy
pip install pandas
# Hướng dẫn sử dụng
Đoạn mã này được viết để phân tích điểm thi cho một lớp học và tính toán các chỉ số thống kê của điểm. Đầu vào của đoạn mã là một file chứa thông tin về các câu trả lời của sinh viên. Đầu ra của đoạn mã là một file mới chứa danh sách mã số sinh viên và điểm số tương ứng.
## Cách sử dụng
1.Nhập tên tập tin khi được yêu cầu

2.Chương trình sẽ cố gắng mở tập tin đó như là tập tin văn bản và đọc nội dung của nó

3.Nếu tập tin được mở thành công, chương trình sẽ phân tích từng dòng dữ liệu để kiểm tra lỗi

4.Các dòng không hợp lệ sẽ bị loại bỏ khỏi tập dữ liệu và được đếm

5.Chương trình sẽ xuất số lượng dòng hợp lệ và không hợp lệ của dữ liệu

6.Chương trình sẽ tính điểm cho từng sinh viên dựa trên một đáp án chuẩn

7.Chương trình sẽ xuất thống kê về các điểm số, bao gồm điểm trung bình, điểm cao nhất, điểm thấp nhất, phạm vi và trung vị

8.Cuối cùng, chương trình sẽ lưu các ID sinh viên và điểm số tương ứng vào một tập tin văn bản mới
## Yêu cầu
Đoạn code yêu cầu một tập tin văn bản với định dạng các giá trị phân tách bằng dấu phẩy (CSV). Mỗi dòng trong tập tin đại diện cho câu trả lời của một sinh viên cho một bài kiểm tra trắc nghiệm. Giá trị đầu tiên trên mỗi dòng là ID của sinh viên, theo sau là 26 giá trị đại diện cho câu trả lời của họ cho các câu hỏi
## Lưu ý
1.Tập tin dữ liệu phải có định dạng chuẩn theo các yêu cầu đã nêu ở trên. Nếu không, chương trình có thể không hoạt động đúng

2.Các lỗi trong tập tin dữ liệu sẽ bị loại bỏ khỏi tập dữ liệu và không được tính vào kết quả cuối cùng

3.Chương trình chỉ tính điểm cho các câu trả lời đúng, không tính điểm cho các câu trả lời sai hoặc không trả lời
## Đóng góp
Nếu bạn phát hiện bất kỳ lỗi nào trong đoạn mã hoặc có ý kiến ​​đóng góp. Chân thành cảm ơn sự đóng góp của bạn!

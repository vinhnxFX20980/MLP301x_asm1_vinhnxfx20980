# MLP301x_asm1_vinhnxfx20980
**Tính toán và phân tích điểm thi (Test Grade Calculator)**
# Cài đặt
1.Cài đặt Python 

2.Cài đặt numpy và pandas bằng cách chạy các lệnh sau trong Command Prompt hoặc Terminal:

```pip install numpy```

```pip install pandas```
# Hướng dẫn sử dụng
Đoạn mã này được viết để phân tích điểm thi cho một lớp học và tính toán các chỉ số thống kê của điểm. Đầu vào của đoạn mã là một file chứa thông tin về các câu trả lời của sinh viên. Đầu ra của đoạn mã là một file mới chứa danh sách mã số sinh viên và điểm số tương ứng.
## Cách sử dụng
1.Khi chạy chương trình sẽ hiển thị Enter a filename:, bạn nhập tên file là class1 (nếu file python nằm cùng folder file class1, nếu khác folder thì phải nhập cả đường dẫn)

Nếu hiển thị Successfully opened class1.txt thì bạn đã nhập đúng, nếu sai sẽ hiển thị File cannot be found. Và bạn phải nhập lại tên file

2.Sau khi chương trình đọc tệp tin thành công, nó sẽ thực hiện phân tích dữ liệu và in ra các kết quả, bao gồm số lượng dòng hợp lệ và không hợp lệ, điểm số trung bình, điểm số cao nhất, điểm số thấp nhất, khoảng điểm và điểm số trung vị. Hiển thị như sau:

**** ANALYZING ****

Invalid line of data: does not contain exactly 26 values:

N00000023,,A,D,D,C,B,D,A,C,C,,C,,B,A,C,B,D,A,C,A,A

Invalid line of data: N# is invalid

N0000002,B,A,D,D,C,B,D,A,C,D,D,D,A,,A,C,D,,A,C,A,A,B,D,D

Invalid line of data: N# is invalid

NA0000027,B,A,D,D,,B,,A,C,B,D,B,A,,A,C,B,D,A,,A,A,B,D,D

Invalid line of data: does not contain exactly 26 values:

N00000035,B,A,D,D,B,B,,A,C,,D,B,A,B,A,A,B,D,A,C,A,C,B,D,D,A,A

**** REPORT ****

Total valid lines of data: 21

Total invalid lines of data: 4

Mean (average) score: 78.0

Highest score: 100

Lowest score: 66

Range of scores: 34

Median score: 76.0

3.Cuối cùng, chương trình sẽ lưu các ID sinh viên và điểm số tương ứng vào một file mới có nội dung chứa ID học sinh và điểm như ví dụ sau:

N00000001,59

N00000002,70
## Yêu cầu
Đoạn code yêu cầu một tập tin văn bản với định dạng các giá trị phân tách bằng dấu phẩy (CSV). Mỗi dòng trong tập tin đại diện cho câu trả lời của một sinh viên cho một bài kiểm tra trắc nghiệm. Giá trị đầu tiên trên mỗi dòng là ID của sinh viên, theo sau là 26 giá trị đại diện cho câu trả lời của họ cho các câu hỏi
## Lưu ý
1.Tập tin dữ liệu phải có định dạng chuẩn theo các yêu cầu đã nêu ở trên. Nếu không, chương trình có thể không hoạt động đúng

2.Các lỗi trong tập tin dữ liệu sẽ bị loại bỏ khỏi tập dữ liệu và không được tính vào kết quả cuối cùng

3.Chương trình chỉ tính điểm cho các câu trả lời đúng, không tính điểm cho các câu trả lời sai hoặc không trả lời
## Đóng góp
Nếu bạn phát hiện bất kỳ lỗi nào trong đoạn mã hoặc có ý kiến ​​đóng góp. Chân thành cảm ơn sự đóng góp của bạn!

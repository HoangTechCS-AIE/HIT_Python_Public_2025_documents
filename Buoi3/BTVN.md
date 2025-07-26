# BTVN Buổi 3

## Yêu cầu:
- Hoàn thành > 70% số lượng bài tập.
- Làm ra các file .py
- Vì các String, List là các object trong Python. Mỗi object sẽ có các phương thức và thuộc tính riêng. Trong khi làm bài, các bạn có thể sử dụng các phương thức để giải quyết vấn đề như `replace()`, `count()`, ... Điều này sẽ rất hữu ích, giúp tiết kiệm thời gian và code ngắn gọn hơn!

## Bài 1:
1. Nhập vào một list có N phần tử là số nguyên (N nhập từ bàn phím).
2. Nhập một số X từ bàn phím, kiểm tra số lần X xuất hiện trong list.
3. Thay thế phần tử từ vị trí 2 -> 7 trong list thành `[8, 5, 4, 0, 1, 3]`.
-  Sử dụng list sau khi thay thế để giải quyết các bài toán tiếp theo.
4. Tìm số lớn nhất và nhỏ nhất trong list.
5. Nhập một số Y tùy chọn từ bàn phím. Chèn số Y vào đầu list.
6. Sau khi chèn số Y, kiểm tra các số trong list có sắp xếp theo thứ tự tăng dần hay giảm dần không. Nếu sắp xếp theo tăng dần thì in ra màn hình “TĂNG”, còn nếu sắp xếp theo thứ tự giảm dần thì in ra màn hình “GIẢM”, nếu không tăng không giảm thì in “NO”.

## Bài 2:
1. Cho một list `a` gồm k phần tử (a và k nhập từ bàn phím). Nhập vào hai số nguyên `n`, `m` là số dòng và số cột của một ma trận.
2. Hãy xây dựng ma trận X(n × m) với các phần tử lần lượt lấy ra từ list ở trên (nếu có thể).
    - Ví dụ: `a = [1, 2, 4, 3, 5, 4, 3, 6, 1, 4, 2, 7, 4, 3, 4, 8, 7, 6]`, `k = 18`. Giả sử `n = 3` và `m = 4`, ma trận X(3 × 4) thu được có dạng `[[1, 2, 4, 3], [5, 4, 3, 6], [1, 4, 2, 7]]`. Nhưng với `n = 3`, `m = 7` ta không thể xây dựng được ma trận.
3. In ra kết quả nếu có thể, không thì in ra “NO”.

## Bài 3:
1. Nhập 2 chuỗi `s1`, `s2` từ bàn phím.
2. In ra đảo ngược của chuỗi `s1`.
3. Nhập vào 2 số nguyên `a`, `b` (1 <= a < b <= len(s2)). In ra chuỗi `s2` sau khi đảo ngược chuỗi từ vị trí `a` đến `b`.
4. In ra chuỗi `s3` là chuỗi `s1` sau khi xóa các kí tự vị trí chẵn.
5. Trả về chuỗi `s4` là đan xen các kí tự của `s1` và `s2`.
    - VD: `s1 = “abc”`, `s2 = “123”` -> `s4 = “a1b2c3”`.
## Bài 4: Chuẩn hóa định dạng họ tên
Bạn Chiến đang rất bận với sự kiện sinh nhật của câu lạc bộ và cần sự trợ giúp của các bạn để xử lý một bài toán nhỏ. Đề bài như sau:
### Mô tả bài toán:
Bạn nhận được một chuỗi văn bản chứa họ và tên của một thành viên trong câu lạc bộ. Tuy nhiên, chuỗi này chưa được viết đúng chuẩn theo định dạng họ tên.
### Yêu cầu:
Hãy viết một chương trình để chuẩn hóa chuỗi họ tên này theo định dạng chuẩn, tức là mỗi từ trong họ tên đều bắt đầu bằng chữ cái viết hoa và các chữ cái còn lại là chữ thường. Định dạng chuẩn của họ tên là: "Họ Tên đệm Tên", với mỗi phần đều bắt đầu bằng chữ cái viết hoa.
- **Input**: Một chuỗi văn bản chứa họ và tên của một thành viên.
- **Output**: Chuỗi văn bản đã được chuẩn hóa theo định dạng chuẩn.
- **Ví dụ**: “lương Thái         sơN” -> “Lương Thái Sơn”.



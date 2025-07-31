## Bài 1: Chuyển đổi tuple và tính trung bình

Viết chương trình thực hiện các yêu cầu sau:
- Cho một tuple chứa n phần tử là các xâu ký tự số (0-9)
- Chuyển đổi thành tuple mới chứa các số tương ứng
- Tính trung bình cộng các phần tử trong tuple kết quả

## Bài 2: Xử lý tập hợp đăng ký học

Thực hiện các thao tác với 2 tập hợp (set):
- Tập A: mã sinh viên đăng ký tại bàn 1
- Tập B: mã sinh viên đăng ký tại bàn 2

### Yêu cầu:
1. In thông tin hai tập hợp
2. Kiểm tra sinh viên đăng ký tại cả hai bàn
3. Tổng hợp danh sách sinh viên đăng ký cả hai bàn
4. Liệt kê sinh viên chỉ đăng ký tại bàn 1

## Bài 3: Tính mức độ hạnh phúc

### Mô tả:
- Cho mảng số nguyên và hai tập A, B
- A: các số bạn thích (+1 điểm)
- B: các số bạn không thích (-1 điểm)

### Input:
```
Dòng 1: n m (số phần tử mảng và số phần tử mỗi tập)
Dòng 2: n số nguyên (mảng input)
Dòng 3: m số nguyên (tập A)
Dòng 4: m số nguyên (tập B)
```

### Output:
- Một số nguyên duy nhất: tổng mức độ hạnh phúc

### Quy tắc tính điểm:
- Phần tử thuộc A: +1
- Phần tử thuộc B: -1
- Không thuộc A,B: +0

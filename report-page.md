# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu

Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm

- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính

### 3.1 Entropy và redundancy

| Input       | Entropy | Redundancy | Nhận xét |
| ----------- | ------: | ---------: | ---------- |
| aaaa        |       a |          a | a          |
| abcd        |       a |          a | a          |
| hello world |       a |          a | a          |

### 3.2 Modulo inverse

|  a |  m | Kết quả mong đợi | Kết quả chương trình |
| -: | -: | -------------------- | ------------------------- |
|  3 |  7 | 5                    | a                         |
| 10 | 17 | 12                   | a                         |
|  6 |  9 | Không tồn tại     | a                         |

## 4. Kết luận


Qua các test trong lab , em hiểu rõ hơn cách entropy phản ánh mức độ ngẫu nhiên của dữ liệu.

Nhận thấy dữ liệu lặp nhiều thì redundancy cao hơn.

Hiểu điều kiện tồn tại của nghịch đảo modulo qua từng trường hợp cụ thể.

Biết cách kiểm tra và so sánh kết quả bằng nhiều input khác nhau.

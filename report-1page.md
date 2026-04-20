# Report 1 Page – FIT4012 Lab 2

## 1. Mục tiêu
- Hoàn thiện mã hóa và giải mã Caesar Cipher.
- Hoàn thiện mã hóa, giải mã và đọc file với Rail Fence Cipher.
- Ghi lại kết quả chạy thử bằng tests, logs và báo cáo.

## 2. Cách làm
- Hoàn thiện Caesar Cipher cho chữ thường, dấu cách và giải mã.
- Hoàn thiện Rail Fence Cipher cho giải mã, giữ dấu cách, kiểm tra đầu vào và đọc file.
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Caesar Cipher
| Input | Key | Ciphertext / Plaintext | Nhận xét |
|---|---:|---|---|
| I LOVE YOU | 3 | L ORYH BRX | Đúng |
| hello world | 5 | mjqqt btwqi | Đúng |
| LORYH BRX | 3 | ILOVE YOU | Đúng |

### 3.2 Rail Fence Cipher
| Input | Rails | Ciphertext / Plaintext | Nhận xét |
|---|---:|---|---|
| I LOVE YOU | 2 | ILV O OEYU | Đúng |
| I LOVE YOU | 4 | I  EYLVOOU | Đúng |
| IOEOLVYU | 2 | ILOVEYOU | Đúng |

### 3.3 Input validation / file input
- Trường hợp đầu vào không hợp lệ: 
  - Input: Hello123 -> Invalid input. Only letters and spaces are allowed.
- Kết quả đọc từ `data/input.txt`:
  - Đọc thành công

## 4. Kết luận
Bài lab giúp em hiểu rõ nguyên lý của các phương pháp mã hóa cổ điển.
Phần khó nhất là giải mã Rail Fence vì cần xử lý zigzag phức tạp.
Sau khi hoàn thành, em đã nắm được cách xây dựng thuật toán và xử lý dữ liệu đầu vào tốt hơn.
# Git 
- Khởi tạo repo local: git init
- Liên kết tới repo local: git remote add origin <url>
- Thêm file vào staging: git add .
- Commit file: git commit -m "<message>"
- Push code: git push code origin main
## 1 số câu lệnh
1. git status: xem trạng thái file
  1.1 File màu xanh: vùng staging
  1.2 File mà đỏ: vùng ửoking dirrectory
2. git log: kiểm tra danh sách commit
## Commit convention
- <type>: <short_description> 
  + type: *chore*: sửa nhỏ lẻ, xóa file k dùng, ...
          *feat*: thêm tính năng, testcáe mới
          *fix*: sửa lỗi
  + <short_description>: mô tả commit
        
# JavaScript
## Comment
- 1 dòng: thêm // trước đoạn comment
- Nhiều dòng: thêm /* dòng đầu tiên và dòng cuối cùng
## Biến
- Là giá trị thay đổi được
- Khai báo: <từ khóa> <tên biến> = <giá trị>
## Hằng
- Là các giá trị k thay đổi được
- Khai báo: <từ khóa> <tên hằng> = <giá trị>
## Data Type
- Primitive type: number, string, boolean, undefined, null, ...
- Reference type: object
## Toán tử so sánh
- So sánh == và ===
- So sánh k bằng: != và !==
- So sánh >, >=, <, <=
## Toán tử logic
- &&: trả về nếu cae 2 vế đúng
- ||: trả về nếu 1 trong 2 vế đúng
## Toán tử một ngôi
- Prefix: ++x; --x, tăng trước trả về sau
- Postfix: x++; x--,trả về trước tăng sau
 ## Toán tử toán học
- Tươg tự các phép tính +, -, *, /
## Câu điều kiện
 ``` cú pháp
 if (<điều kiện>) {
    // code
 }
 ```
 ## Vòng lặp
 ```cú pháp
 for (<đièu kiện>; <đk lặp>; <cập nhật>) {
    //code
 }
 ```


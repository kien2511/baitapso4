# baitapso4
Bài tập số 4 của sinh viên:K225480106032 - Nguyễn Trung Kiên - Môn hệ quản trị cơ sở dữ liệu
## yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

## các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

## Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  

## deadline: 15/4/2025

## Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
tạo bảng giáo viên khóa chính là giáo viên

![image](https://github.com/user-attachments/assets/d52ed241-9cc6-4b7e-ada0-3cbb66e1c665)


tạo bảng môn học khóa chính là mã môn học


![image](https://github.com/user-attachments/assets/095c4dba-2c3c-4312-82c7-ccf0ed2de5b8)


tạo bảng phòng học với mã phòng là khóa chính 


![image](https://github.com/user-attachments/assets/48c91d0c-f45a-41f0-b675-5c3f179cfa7a)


tạo bảng lớp học phần với mã lớp học phần là khóa chính 


![image](https://github.com/user-attachments/assets/0486e34d-760d-44b8-9e9b-1091476fed7a)

tạo bảng lịch dạy với mã phòng là khóa chính 


![image](https://github.com/user-attachments/assets/1793aa5b-e3b2-4cd0-b80c-db4c7afdbcfb)



khóa ngoại 

tạo một cột mã môn học thành khóa ngoại trỏ đến cột mã môn học trong bảng môn học

![image](https://github.com/user-attachments/assets/1443f410-801a-4d5a-9bd5-0f49aea9b18b)


tạo một cột mã giáo viên thành khóa ngoại trỏ đến cột mã giáo viên trong bảng giáo viên

![image](https://github.com/user-attachments/assets/0dc4dba9-64a1-40ef-a452-969ffb6c5b8a)

tạo cột lớp mã lớp học phần thành khóa ngoại trỏ đến cột mã lớp phòng học trong bảng lớp học phần

![image](https://github.com/user-attachments/assets/84b550eb-bee5-49f3-bcf2-4091e10921d3)

tạo một cột mã phòng thành khóa ngoại trỏ đến cột mã phòng trong bảng lịch dạy

![image](https://github.com/user-attachments/assets/21ac2d37-7e81-449a-bd99-eed8167d2eed)

BẢNG THỰC THỂ LIÊN KẾT

![image](https://github.com/user-attachments/assets/d811ee8b-296d-4ff3-92b3-808ad33d4cad)

BẢNG TKB CỦA LỚP

![image](https://github.com/user-attachments/assets/c1d14655-52c7-40fa-aeff-5450832d7052)

LƯU BẰNG MYCROSOFT EXCEL 97- 2003 WORKBOOK .XLS


![image](https://github.com/user-attachments/assets/9786bd58-4cda-4dbf-9fd2-a1177f01b512)


VÀO SQL SEVER VÀO DATABASE CLICK CHUỘT PHẢI VÀO BTVN4 CHỌN TASK

![image](https://github.com/user-attachments/assets/4dca6981-130b-4301-93f7-725a64a112e6)

CHỌN INPORT DATA
![image](https://github.com/user-attachments/assets/10d868e4-9add-482c-9be6-d771d4a830de)

CHỌN MYCROSOFT EXCEL 

![image](https://github.com/user-attachments/assets/e7e34a36-78f0-4c66-9ddb-28e4b7154d2b)

CHỌN NEXT SAU ĐÓ CÓ BẢNG INPORT DATA
![image](https://github.com/user-attachments/assets/05236ed8-fd27-4ec1-9784-d8ca29428bf4)

SHOW BẢNG DATA
![image](https://github.com/user-attachments/assets/59639fab-1d63-4fb8-9722-f50e6f040acb)

CÂU LỆNH TRUY VẤN 
NGÀY 01/04/2025 CÓ GIẢNG VIÊN ĐỖ DUY CỐP BẬN TỪ 8H00 - 11H00

![image](https://github.com/user-attachments/assets/9a480591-8b9f-4ad3-9caa-4677d7172cd5)

NGÀY 13/04/2025 CÓ 2 GIẢNG VIÊN BẬN TỪ 8H00 - 11H00
![image](https://github.com/user-attachments/assets/f00a2f33-5b2e-409f-8812-73c669914ad1)





















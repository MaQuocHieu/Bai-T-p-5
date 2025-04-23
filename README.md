# BÀI TẬP 5
# MA QUỐC HIẾU-

# BÀI TẬP VỀ NHÀ 05, Môn Hệ quản trị csdl.

SUBJECT: Trigger on mssql

A. Trình bày lại đầu bài của đồ án PT&TKHT:
1. Mô tả bài toán của đồ án PT&TKHT, 
   đưa ra yêu cầu của bài toán đó
2. Cơ sở dữ liệu của Đồ án PT&TKHT :
   Có database với các bảng dữ liệu cần thiết (3nf),
   Các bảng này đã có PK, FK, CK cần thiết
 
B. Nội dung Bài tập 05:
1. Dựa trên cơ sở là csdl của Đồ án
2. Tìm cách bổ xung thêm 1 (hoặc vài) trường phi chuẩn
   (là trường tính toán đc, nhưng thêm vào thì ok hơn,
    ok hơn theo 1 logic nào đó, vd ok hơn về speed)
   => Nêu rõ logic này!
3. Viết trigger cho 1 bảng nào đó, 
   mà có sử dụng trường phi chuẩn này,
   nhằm đạt được 1 vài mục tiêu nào đó.
   => Nêu rõ các mục tiêu 
4. Nhập dữ liệu có kiểm soát, 
   nhằm để test sự hiệu quả của việc trigger auto run.
5. Kết luận về Trigger đã giúp gì cho đồ án của em.

## Bài làm
Đồ án : Phân tích thiết kế hệ QL thư viện trường ĐHKT Công Nghiệp Thái Nguyên

## Nội dung :
## Tạo bảng Database tên QL THUVIEN DHKTCN 

![image](https://github.com/user-attachments/assets/e47fbf44-b19c-40fd-83cd-99cbbaf1b07a)

## Gồm các bảng sau :
## BẢNG ChiTietPhieuMuon

![image](https://github.com/user-attachments/assets/cf11cdb4-99bc-4437-b679-0e5332c512c5)

## Bảng NhanVien

![image](https://github.com/user-attachments/assets/66d041ca-c62e-4268-b59d-0512d415ab3e)

## Bảng PhieuMuon

![image](https://github.com/user-attachments/assets/d860070a-f4bd-4722-932b-c510a234e1cd)

## Bảng PhieuTra

![image](https://github.com/user-attachments/assets/fa01c06b-7227-4e8b-ad5f-620222a25dde)

## Bảng Sach

![image](https://github.com/user-attachments/assets/3f942fca-d209-4d4f-b14f-0e5bd8743b8f)

## Bảng SinhVien

![image](https://github.com/user-attachments/assets/c3235c0a-befe-4ea7-a604-eefd97261c3d)

## Bảng TheLoai

![image](https://github.com/user-attachments/assets/4d19bbf2-9335-46b1-929e-ca50787ceb6d)

## Bảng Database diagrams

![Screenshot 2025-04-23 211613](https://github.com/user-attachments/assets/54df3a3e-b81c-406c-a43e-95a7b0dd1654)

# Nội dung triger : 
- Trigger này là cảnh báo xem sinh viên đã trả sách đúng ngày hay chưa
## Code

![Screenshot 2025-04-23 215356](https://github.com/user-attachments/assets/92fdd65b-b8f6-4ee0-9da6-6af7fce1c10d)

## Kiểm tra kết quả

![Screenshot 2025-04-23 215411](https://github.com/user-attachments/assets/b241145c-7634-412c-9592-bcd9bd785911)

## Bài học rút ra từ triger
 - Trigger này sẽ giúp cho nhân viên ở thư viên biết những sinh viên nào chưa trả sách và sẽ thông báo vào email của sinh viên đó. Nếu sinh đó làm mất sách sẽ phải đóng tiền phạt mà đã nội quy đã quy định.



















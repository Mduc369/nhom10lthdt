Các lớp vấn đề đối tượng
1.lớp (class)
lớp là khôn mẫu để mô tả một nhóm đối tượng có đặc điểm và hành vi giống nhau
một lớp thường có:
Thuộc tính (attribute): mô tả đặc điểm của đối tượng
Phương thức (method): mô tả hành động , hành vi của đối tượng
ví dụ
class SinhVien {
    String hoTen;
    int tuoi;
    double diem;

    void hienThiThongTin() {
        System.out.println(hoTen + " - " + tuoi + " - " + diem);
        Ở đây:
              hoTen, tuoi, diem → thuộc tính
              hienThiThongTin() → phương thức
              SinhVien → lớp
 2. Đối tượng (Object)
Đối tượng là một thể hiện (instance) cụ thể của một lớp.
Ví dụ:
SinhVien sv1 = new SinhVien();
sv1.hoTen = "Nguyen Van A";
sv1.tuoi = 20;
sv1.diem = 8.5;
sv1 là đối tượng được tạo ra từ lớp SinhVien.
Có thể tạo nhiều đối tượng từ cùng một lớp:

SinhVien sv1 = new SinhVien();
SinhVien sv2 = new SinhVien();
SinhVien sv3 = new SinhVien();
Cả 3 đều thuộc lớp SinhVien, nhưng mỗi đối tượng có dữ liệu riêng.
3. Mối quan hệ giữa lớp và đối tượng:
Lớp → khuôn mẫu
Đối tượng → sản phẩm cụ thể được tạo từ khuôn mẫu
Ví dụ đời thực:
Lớp: Xe
Đối tượng: xe Toyota, xe Honda, xe Ford
Thuộc tính: màu, hãng, tốc độ
Phương thức: chạy(), phanh(), tăngToc() 
4. Các vấn đề cốt lõi của OOP
Đóng gói (Encapsulation) – gom dữ liệu và phương thức vào một lớp, kiểm soát quyền truy cập.
Kế thừa (Inheritance) – lớp con kế thừa thuộc tính,phương thức của lớp cha.
Đa hình (Polymorphism) – cùng một lời gọi nhưng có thể thực hiện theo nhiều cách khác nhau.
Trừu tượng (Abstraction) – thể hiện những đặc điểm cần thiết, che giấu phần triển khai phức tạp.

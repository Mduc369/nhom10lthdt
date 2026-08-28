 hung-khainiem
# Giới thiệu về lập trình hướng đối tượng 
1. Phương pháp tiếp cận của lập trình truyền thống.
1.1. Lập trình tuyến tính:
  - Tư duy: Thực thi theo lối tuần tự từ trên xuống dưới, câu lệnh trước chạy xong mới đến câu lệnh sau.
  - Đặc trưng: Đơn giản và đơn luồng.
  - Ưu điểm: Mã nguồn đơn giản, trực diện, dễ đọc với các bài toán quy mô nhỏ.
  - Nhược điểm: Không thể mở rộng để giải quyết các hệ thống/ứng dụng thực tế phức tạp; mã nguồn dễ bị trùng lặp và cực kỳ khó bảo trì.
1.2. Lập trình cấu trúc:
  - Tư duy: Áp dụng phương pháp "Chia để trị". Chương trình lớn được phân rã thành các chương trình con, hàm hoặc thủ tục nhỏ hơn.
  - Đặc trưng: Chương trình = cấu trúc dữ liệu + giải thuật.
  - Ưu điểm: chương trình dễ hiểu dễ theo dõi.
  - Nhược điểm: Không phù hợp với phần mềm lớn, khó bảo trì,...
2. Phương pháp tiếp cận hướng đối tượng.
2.1. Phương pháp lập trình hướng đối tượng
  - Khắc phục hạn chế cũ: Giải quyết vấn đề lộ/sửa nhầm dữ liệu toàn cục của lập trình cấu trúc.
  - Đóng gói dữ liệu: Bó dữ liệu (thuộc tính) và hàm xử lý (phương thức) chung vào một đối tượng duy nhất để bảo vệ an toàn.
  - Tái sử dụng mã nguồn: Cho phép lớp con dùng lại mã nguồn của lớp cha (kế thừa), giúp tiết kiệm thời gian viết code.
2.2. Phương pháp phân tích và thiết kế hướng đối tượng.
  - Quy trình 6 bước để chuẩn bị trước khi viết chương trình:
      + Mô tả bài toán & Đặc tả yêu cầu: Hiểu rõ bài toán và xác định hệ thống cần làm những chức năng gì.
      + Trích chọn đối tượng: Nhặt ra các thực thể cốt lõi trong bài toán (Ví dụ: Sinh viên, Giảng viên, Lớp học).
      + Mô hình hóa lớp đối tượng: Gom các đối tượng giống nhau thành một Lớp (Class), quy định rõ chứa dữ liệu gì và làm được gì.
      + Thiết kế tổng quan & Chi tiết: Dựng khung kiến trúc toàn hệ thống và vẽ sơ đồ chi tiết cách các đối tượng phối hợp với nhau.
3. Các khái niệm cơ bản
3.1 Đối tượng
  - Thực thể cụ thể trong thực tế hoặc chương trình, gồm dữ liệu (thuộc tính) và hành vi (phương thức).
3.2. Lớp đối tượng
  - Lớp là 1 khái niệm trừu tượng, dùng để chỉ tập hợp các đối tượng có mặt trong hệ thống.
  - Đối tượng là 1 thực thể tồn tại bên trong hệ.
  - Thuộc tính của lớp tương ứng với thuộc tính của đối tượng.
  - Một lớp có khả khả năng sau:
      + Chỉ có thuộc tính, không có phương thức.
      +  Chỉ có phương thức, không có thuộc tính.
      +  Có cả 2 thuộc tính.
3.3. Trừu tượng hóa theo chức năng
  - Tập trung vào việc đối tượng làm được gì (chức năng) mà giấu đi logic cài đặt chi tiết bên trong.
3.4. Trừu tượng hóa theo dữ liệu
  - Chỉ giữ lại các thông tin dữ liệu quan trọng phục vụ cho bài toán và ẩn đi sự phức tạp trong việc lưu trữ/biểu diễn bộ nhớ.
  - Ví dụ: Quản lý Sinh viên chỉ cần giữ thông tin Mã SV, Họ tên, Điểm chứ không cần lưu nhóm máu, chiều cao.
3.5. Khái niệm kế thừa
  - Lớp con tự động có lại các thuộc tính và phương thức của lớp cha mà không cần viết lại mã nguồn.
  - Ví dụ: Lớp Hình tròn kế thừa từ lớp Hình học.
3.6. Khái niệm đóng gói (Encapsulation)
  - Gom dữ liệu và hàm xử lý vào chung một Lớp, đồng thời che giấu dữ liệu bên trong (private) để tránh sự can thiệp trái phép từ bên ngoài.
3.7. Khái niệm đa hình
  - Cùng một hành động (tên phương thức) nhưng các đối tượng khác nhau sẽ thực hiện theo những cách khác nhau.
# nhom10lthdt
Tóm tắt kiến thức về lập trình hướng đối tượng:
+ Phần 1: Khái niệm và giới thiệu về lập trình hướng đối tượng
+ Phần 2: Các mở rộng của C++ trong lập trình hướng đối tượng
+ Phần 3: Các lớp và đối tượng trong lập trình hướng đối tượng
I: Khái niệm và giới thiệu về lập trình hướng đối tượng
1. Các phương pháp tiếp cận lập trình
Gồm có:
+ Lập trình tuyến tính
+ Lập trình cấu trúc
3. Lớp đối tượng
4. Sự trừu tượng hóa
+ Theo chức năng
+ Theo dữ liệu
5. Sự đóng gói
6. Sự kế thừa
7. Thành phần private và public
II: Các mở rộng của C++ trong lập trình hướng đối tượng 
1. Lịch sử của C++
2. Các mở rộng của C++
III: Các lớp và đối tượng trong lập trình hướng đối tượng 
1. Các lớp
2. Con trỏ đối tượng
3. Các hàm 
main

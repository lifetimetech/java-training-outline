# Java Training Outline 

__Tài liệu này dùng để làm outline training cho sinh viên thực tập WEB Java.__

----

## Giới thiệu.

Giới thiệu cho các sinh viên tổng quan về 

* Web service - mô hình MVC, Restful 
* Ngôn ngữ lập trình Java
* Một database (recommend Mysql) 
* Framework Spring - Spring boot

Thời gian training khoảng 2 tháng.

Trong khoảng thời gian này sinh viên sẽ được được hướng dẫn thực tập với ngôn ngữ Java, sau đó là sử dụng Spring boot để xây dựng các trang web nhỏ. Trong các giai đoạn sẽ có đánh giá và rút kinh nghiệm giữa người hướng dẫn và các sinh viên (Lưu ý: cần đánh giá và phản hồi của cả sinh viên với giáo trình và người hướng dẫn)

Mục tiêu sau quá trình thực tập, sinh viên có thể tham gia các dự án Java Spring

### Outline.
| STT  | Nội dung | Yêu cầu | Thời gian (h) |
| ------------- | ------------- | ------------- | ------------- |
|| **JAVA CORE** | | **48** |
| 1 | Làm quen với Java | - Hiểu các khái niệm cơ bản của Java cũng như các đặc điểm của nó.<br/> - Cài đặt môi trường phát triển.<br/> - Viết chương trình java đơn giản. Đọc dữ liệu từ bàn phím và xuất dữ liệu ra màn hình. | 8 |
| 2 | Quản lý source code với Git | - Cơ bản về Git <br/> - GitHub và Bitbucket | 8 | 
| 3 | Biến, kiểu dữ liệu, các toán tử và câu lệnh if, switch | - Sử dụng thành thạo các loại toán tử <br/> - Biết các xây dựng các loại biểu thức <br/> - Sử dụng thành thạo câu lệnh rẽ nhánh (if) <br/> - Sử dụng thành thạo câu lệnh lựa chọn (switch) <br/> - Sử dụng try...catch để kiểm soát lỗi | 8 |
| 4 | Mảng, ArrayList, vòng lặp | - Biết cách sử dụng và làm việc với mảng trong Java <br/> - Hiểu và sử dụng được ArrayList <br/> - Hiểu và sử dụng được các hàm tiện ích của Collection <br/> - Sử dụng thành thạo các lệnh lặp (for, while, do...while) và ngắt vòng lặp (break, continue) | 8 |
| 5 | Chuỗi và biểu thức chính qui | - Hiểu cũng như biết cách sử dụng chuỗi và biểu thức chính qui | 4 |
| 6 | Xử lý ngoại lệ trong Java | - Biết cách sử dụng try ... catch để xử lý ngoại lệ <br/> - Biết các sử dụng từ khóa throws và throw | 4 |
| 7 | Lớp, đối tượng, kế thừa | - Hiểu khái niệm về lớp và đối tượng <br/> - Mô hình hóa đối tượng và lớp <br/> - Định nghĩa được các hàm <br/> - Nắm vững được sự phân cấp kế thừa, lớp và các phương thức trừu tượng <br/> - Tái sử dụng các lớp sẵn có <br/> - Biết cách ghi đè các phương thức | 8 |
| | **HỆ QUẢN TRỊ CSDL MYSQL** | | **16** |
| 8 | Cơ bản về MySql | - MySql là gì? <br/> - MySql có thể làm được những gì? <br/> - Cài đặt môi trường sử dụng MySql | 4 |
| 9 | Các kiểu dữ liệu trong MySql | - Hiểu và biết cách sử dụng các kiểu dữ liệu trong các trường hợp | 4 |
| 10 | Các câu lệnh cơ bản | Biết các sử dụng các câu lệnh cơ bản của MySql  <br/> - SELECT - Lấy dữ liệu từ DB <br/> - UPDATE - Cập nhật dữ liệu trong DB <br/> - DELETE - Xóa dữ liệu trong DB <br/> - INSERT INTO - Thêm dữ liệu mới vào DB <br/> - CREATE DATABASE - Tạo một DB mới <br/> - ALTER DATABASE - Cập  nhật một DB <br/> - CREATE TABLE - Tạo bảng mới trong DB <br/> - ALTER TABLE - Cập nhật bảng <br/> - DROP TABLE - Xóa bảng <br/> - CREATE INDEX - Tạo index <br/> - DROP INDEX - Xóa một index <br/> - JOIN - Nối bảng | 8 |
| | **SPRING FRAMEWORK - SRING BOOT** | | **80** |
| 11 | Tìm hiểu cơ bản về Spring và Spring Boot | - Spring boot là gì? Tại sao lại sử dụng? <br/> - Các tính năng của Spring boot? <br/> - Cài đặt môi trường phát triển  <br/> - Tạo project đầu tiên | 8 |
| 12 | Cấu trúc code và coding conventions | - Nắm được cấu trúc code cơ bản của một dự án spring boot <br/> - Biết và vận dụng được coding conventions vào dự án | 4 |
| 13 | Maven và Gradle | - Maven, Gradle là gì? <br/> - So sánh Maven và Gradle <br/> - Biết cách sử dụng Maven và Gradle | 4 |
| 14 | Làm việc với cơ sở dữ liệu MySql | - Sử dụng JPA, Hibernate để thao tác với CSDL MySql | 16 |
| 15 | Dựng giao diện với Thymeleaf | - Biết cách sử dụng Thymeleaf để dựng giao diện | 16 |
| 16 | Spring Security | - Sử dụng Spring Security để tạo trang Đăng Ký và Đăng Nhập | 16 |
| 17 | Validation | - Validation trong Spring boot | 16 | 
| | **BÀI TẬP TỔNG KẾT** | | **56** |
| 18 | Yêu cầu | - Hoàn thiện một trang web đơn giản với các chức năng: thêm, sửa, xóa, tìm kiếm <br/> - Có ít nhất 2 đối tượng với các mối quan hệ 1-1, 1-n <br/> - Có thực hiện Validation <br/> - Web client site hiển thị đẹp, có sử dụng JavaScript, Html, CSS, Bootstrap <br/> - Hiển thị tốt trên các trình duyệt Chrome, Firefox, IE bản mới nhất <br/> - Làm slide thuyết trình và báo cáo | 56 |
| | | | |
| | | **TỔNG** | **200** |

----

### Tài liệu dùng nội bộ công ty TNHH Công Nghệ và Cuộc Sống

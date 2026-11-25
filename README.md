<div align="center">

# Xin chào, mình là Hồ Sỹ Thành 👋
### 💻 Java Backend Developer Intern (Spring Boot)

🎓 Sinh viên năm cuối ngành **Hệ thống thông tin** — **Đại học Công nghiệp Hà Nội (HaUI)**  
🎯 Đang tìm kiếm cơ hội **Thực tập sinh Java Backend (Spring Boot)** tại **Hà Nội**  

[![Email](https://img.shields.io/badge/Email-thanhhossy0606%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thanhhossy0606@gmail.com)
[![Phone](https://img.shields.io/badge/Điện_thoại-0974_932_089-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:0974932089)
[![Location](https://img.shields.io/badge/Địa_chỉ-Hà_Nội%2C_Việt_Nam-0A66C2?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 👨‍💻 Giới Thiệu Bản Thân

- 🏫 **Học vấn**: Sinh viên năm cuối chuyên ngành **Hệ thống thông tin** tại **Đại học Công nghiệp Hà Nội (HaUI)**.
- 🌱 **Định hướng chuyên môn**: Phát triển hệ thống Backend với **Java Core, Spring Boot, Spring Data JPA, Spring Security, RESTful API** và cơ sở dữ liệu quan hệ **MySQL**.
- 💼 **Mục tiêu nghề nghiệp**: Mong muốn ứng tuyển vị trí **Thực tập sinh Java Backend (Spring Boot)** để tham gia phát triển các dự án thực tế, rèn luyện tư duy thiết kế hệ thống, tối ưu truy vấn cơ sở dữ liệu và quy trình làm việc nhóm chuyên nghiệp.
- 📫 **Liên hệ trực tiếp**:
  - **Email**: [thanhhossy0606@gmail.com](mailto:thanhhossy0606@gmail.com)
  - **Số điện thoại / Zalo**: `0974 932 089`
  - **Địa chỉ**: Hà Nội, Việt Nam

---

## 🛠️ Tech Stack & Công Cụ

### **Ngôn Ngữ, Framework & Cơ Sở Dữ Liệu**
<p align="left">
  <img src="https://img.shields.io/badge/Java_Core-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java Core" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Data JPA" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/RESTful_API-005571?style=for-the-badge&logo=fastapi&logoColor=white" alt="RESTful API" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white" alt="Thymeleaf" />
</p>

### **Build Tool, Quản Lý Mã Nguồn & Kiểm Thử API**
<p align="left">
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,spring,mysql,maven,git,github,postman,docker" alt="Skill Icons" />
</p>

---

## 🚀 Dự Án Tiêu Biểu

### 📚 [nhanambook — Hệ Thống Thương Mại Điện Tử & Quản Lý Nhà Sách Nhã Nam](https://github.com/thanhhosy0606-cell/nhanambook)
> **Loại dự án**: Dự án nhóm gồm 5 thành viên
> **Công nghệ & Ngôn ngữ sử dụng**: `Java 21`, `Spring Boot 3.3`, `Spring Data JPA / Hibernate`, `Spring Security Crypto (BCrypt)`, `RESTful API & Webhook`, `Thymeleaf`, `MySQL 8.0`, `Maven`, `PayOS Java SDK (VietQR)`, `MoMo Payment API`, `OAuth 2.0`, `Git/GitHub`, `Postman`.

#### 👨‍💻 **Vai trò & Phần việc của Hồ Sỹ Thành trong dự án**:
1. **Phân hệ Quản lý Loại sách (Category Management)**:
   - Thiết kế Entity `LoaiSach`, DTO `LoaiSachFormDto`, Repository và `LoaiSachService`.
   - Xây dựng đầy đủ chức năng **CRUD loại sách**, tìm kiếm kết hợp lọc theo trạng thái (`HOAT_DONG` / `NGUNG`) và thống kê số lượng đầu sách theo từng danh mục.
   - Xử lý **ràng buộc toàn vẹn dữ liệu**: Kiểm tra và ngăn chặn xóa danh mục đang có đầu sách liên kết, hướng dẫn quản trị viên chuyển trạng thái hoặc điều chuyển sách an toàn.
2. **Phân hệ Đặt hàng & Xử lý Đơn hàng (Checkout & Order Management)**:
   - Xây dựng luồng đặt hàng (`OrderController`, `DonHangService`) từ giỏ hàng, kiểm tra tồn kho, tự động điền sổ địa chỉ nhận hàng mặc định.
   - **Thuật toán tính phí vận chuyển động theo khu vực**: Tự động phân loại phí giao hàng theo tỉnh/thành phố (Nội thành Hà Nội/TP.HCM `15.000đ`, Đà Nẵng/Hải Phòng/Cần Thơ `25.000đ`, tuyến tỉnh xa `35.000đ`) và miễn phí vận chuyển (`0đ`) cho đơn hàng từ `300.000đ` hoặc khi áp dụng mã `FREESHIP`.
   - **Áp dụng Mã giảm giá & Ví Voucher**: Kiểm tra tính hợp lệ, giá trị đơn hàng tối thiểu, khấu trừ số lượng mã giảm giá và đồng bộ trạng thái trong Transaction (`@Transactional`).
   - **Thanh toán đa kênh & Quản lý vòng đời đơn hàng**: Kết nối thanh toán trực tuyến qua **VietQR (PayOS)**, **Ví MoMo**, thanh toán khi nhận hàng (**COD**); cho phép khách hàng đổi phương thức thanh toán, hủy đơn, xuất/tải hóa đơn PDF.
   - **Tự động hủy đơn quá hạn thanh toán (`@Scheduled` Background Job)**: Quét định kỳ mỗi 60 giây để tự động hủy các đơn hàng online quá hạn 15 phút chưa thanh toán, tự động **hoàn lại tồn kho sách** và **hoàn trả lượt dùng voucher**.
   - **Quản trị đơn hàng (Admin Order Management)**: Tìm kiếm, phân trang và lọc đơn hàng đa tiêu chí bằng JPA `Specification`, cập nhật trạng thái đơn hàng theo quy trình nghiệp vụ.

#### ✨ **Các chức năng nổi bật khác của hệ thống**:
- 🛍️ **Storefront & Giỏ hàng**: Tìm kiếm, lọc sách đa tiêu chí, gợi ý sách thông minh, đánh giá & bình luận sản phẩm, hiển thị trực quan nhãn sách hết hàng/ngừng kinh doanh.
- 🔐 **Xác thực & Bảo mật**: Đăng nhập/Đăng ký bảo mật với BCrypt, tích hợp đăng nhập Google & Facebook OAuth 2.0, khôi phục mật khẩu qua Gmail SMTP.
- 📊 **Báo cáo & Thống kê Doanh thu**: Dashboard thống kê doanh thu theo ngày/tháng/năm trực tiếp bằng truy vấn SQL, bảng xếp hạng Top khách hàng và đo lường hiệu quả mã giảm giá.

---

## 📊 Thống Kê Hoạt Động GitHub

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=thanhhosy0606-cell&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub Stats" />
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thanhhosy0606-cell&layout=compact&langs_count=6&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

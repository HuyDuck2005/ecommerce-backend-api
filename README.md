E-Commerce Backend API & Guitar Shop
Dự án Backend phục vụ hệ thống E-Commerce, tập trung vào thiết kế cơ sở dữ liệu có cấu trúc và phát triển RESTful API hiệu năng cao cho giao dịch thanh toán.

🚀 Giới thiệu dự án
Đây là hệ thống Backend được phát triển nhằm tối ưu hóa quy trình quản lý kho hàng và xử lý đơn hàng cho cửa hàng Guitar. Dự án tập trung vào tính bảo mật, khả năng mở rộng và hiệu suất truy vấn.

🛠 Tech Stack
Runtime: Node.js, Express

Database: PostgreSQL (quản lý bởi Knex.js)

API: RESTful API, Swagger documentation

Security: JWT (Authentication), bcryptjs (Password Hashing)

DevOps: Docker, Docker Compose

Logging: Pino Logger

✨ Tính năng chính
Quản trị người dùng: Đăng ký, đăng nhập bảo mật với JWT và xác thực phân quyền.

Quản lý dữ liệu: Database Schema tối ưu với 10+ bảng (User, Product, Order, Transaction, v.v.).

Xử lý đơn hàng: RESTful API cho phép thực hiện giao dịch thanh toán và cập nhật tồn kho.

Tài liệu API: Tích hợp Swagger để dễ dàng kiểm thử và theo dõi các endpoint.

📂 Cấu trúc dự án
Plaintext
├── controllers/    # Xử lý logic nghiệp vụ
├── db/             # Cấu hình migrations và seeds
├── middlewares/    # Xử lý xác thực, log và validation
├── models/         # Định nghĩa các model dữ liệu (Database Schema)
├── routers/        # Định nghĩa các endpoint API
├── services/       # Layer xử lý logic trung gian
├── validators/     # Kiểm soát dữ liệu đầu vào
└── server.js       # File khởi chạy ứng dụng
⚙️ Hướng dẫn cài đặt
Clone repository:

Bash
git clone https://github.com/HuyDuck2005/ecommerce-backend-api
cd ecommerce-backend-api
Cài đặt dependencies:

Bash
npm install
Cấu hình môi trường:
Tạo file .env và thiết lập các biến môi trường (Database URL, JWT Secret, v.v.) dựa trên file mẫu.

Khởi chạy hệ thống (Docker):

Bash
docker-compose up -d
📧 Liên hệ
Tác giả: Vũ Huy Đức (HUYDUCK)

GitHub: github.com/HuyDuck2005

Email: vuhuyduc1234dn@gmail.com

# E-Commerce Backend API

Dự án Backend phục vụ hệ thống E-Commerce, tập trung vào thiết kế cơ sở dữ liệu có cấu trúc và phát triển RESTful API hiệu năng cao cho quản lý kho hàng và giao dịch.

## 🚀 Giới thiệu dự án
Đây là hệ thống Backend được phát triển nhằm tối ưu hóa quy trình quản lý kho hàng và xử lý đơn hàng. Dự án tập trung vào tính bảo mật, khả năng mở rộng và hiệu suất truy vấn dữ liệu.

## 🛠 Công nghệ sử dụng (Tech Stack)
* **Runtime:** Node.js, Express
* **Database:** PostgreSQL (Quản lý qua Knex.js)
* **API:** RESTful API, Swagger Documentation
* **Security:** JWT (Authentication), bcryptjs (Password Hashing)
* **DevOps:** Docker, Docker Compose
* **Logging:** Pino Logger

## ✨ Tính năng chính
* **Quản trị người dùng:** Đăng ký, đăng nhập bảo mật với JWT và xác thực phân quyền (Authorization).
* **Quản lý dữ liệu:** Database Schema tối ưu hóa với hơn 10 bảng (User, Product, Order, Transaction, v.v.).
* **Xử lý đơn hàng:** RESTful API hiệu năng cao phục vụ quản lý giao dịch thanh toán và tồn kho.
* **Tài liệu hóa:** Tích hợp Swagger để kiểm thử và theo dõi các endpoint dễ dàng.

## 📂 Cấu trúc dự án
```text
├── controllers/    # Xử lý logic nghiệp vụ
├── db/             # Cấu hình migrations và seeds
├── middlewares/    # Xử lý xác thực, log và validation
├── models/         # Định nghĩa các model dữ liệu (Database Schema)
├── routers/        # Định nghĩa các endpoint API
├── services/       # Layer xử lý logic trung gian
├── validators/     # Kiểm soát dữ liệu đầu vào
└── server.js       # File khởi chạy ứng dụng

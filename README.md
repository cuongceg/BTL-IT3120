# Hệ Thống Điều Khiển và Giám Sát Bơm IoT
## Mục lục
1. [Giới thiệu dự án](#giới-thiệu-dự-án)
2. [Cấu trúc thư mục](#cấu-trúc-thư-mục)
3. [Công nghệ sử dụng](#công-nghệ-sử-dụng)

## Giới thiệu dự án
Dự án xây dựng hệ thống điều khiển và giám sát bơm nước sử dụng công nghệ IoT, cho phép người dùng theo dõi trạng thái, điều khiển bật/tắt bơm từ xa, nhận cảnh báo lỗi và quản lý thiết bị từ mọi nơi.

Hệ thống hỗ trợ ba vai trò chính:

- Người dùng: quan sát trạng thái bơm, điều khiển từ xa, nhận thông báo sự cố.

- Kỹ sư: tạo loại thiết bị, hỗ trợ khách hàng.

- Quản trị viên: quản lý tài khoản và thiết bị, phân quyền và giám sát toàn bộ hệ thống.
## Cấu trúc thư mục
- **.github/**: Thư mục cấu hình cho GitHub Actions (CI/CD) chuyển từ file .drawio sang .png.
- **../generated/**: Thư mục chứa các ảnh được generated của Github Action.
- **Activity diagram/**: Chứa các sơ đồ hoạt động của hệ thống.
- **Class diagram/**: Chứa các sơ đồ lớp.
- **Database diagram/**: Chứa các sơ đồ cơ sở dữ liệu.
- **Sequence diagram/**: Chứa các sơ đồ trình tự.
- **State machine diagram/**: Chứa các sơ đồ trạng thái.
- **Usecase diagram/**: Chứa các sơ đồ usecase.
- **README.md**: Tài liệu hướng dẫn và mô tả dự án.

---

## Công nghệ sử dụng

- **draw.io, visual paradigm**: Công cụ vẽ sơ đồ UML trực tuyến.
- **MongoDb modeller**: Công cụ vẽ sơ đồ database từ MongoDb.
- **GitHub Actions**: Tự động hóa quy trình CI/CD.
- **Markdown**: Viết tài liệu hướng dẫn.

---
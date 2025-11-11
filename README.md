# java-florist
Flower selection and online ordering website using ASP.NET Core Web API and React
Hướng dẫn Thiết lập Môi trường cho Thành viên Nhóm
Mỗi thành viên trong nhóm cần thực hiện 3 bước chính: Clone, Thiết lập Backend, và Thiết lập Frontend.

Bước 1: Clone Repository
Các thành viên cần phải có quyền truy cập vào repository java-florist của bạn (nếu là repository riêng tư, bạn phải thêm họ làm cộng tác viên).

Lấy URL Clone: Yêu cầu các thành viên truy cập vào repo java-florist trên GitHub, sau đó click vào nút < > Code và sao chép URL HTTPS hoặc SSH URL.

Clone về máy: Mở Terminal (hoặc Git Bash) trên máy của họ, điều hướng đến thư mục mà họ muốn lưu trữ dự án (ví dụ: thư mục Projects), và chạy lệnh sau (thay thế URL bằng URL thực tế):

Bash

git clone https://fptshop.com.vn/tin-tuc/danh-gia/repository-la-gi-172536
Ví dụ:

Bash

git clone https://github.com/your-username/java-florist.git
Điều hướng vào thư mục dự án:

Bash

cd java-florist
Bước 2: Thiết lập Backend (ASP.NET Core Web API)
Mục tiêu là khôi phục các gói NuGet (dependencies) cần thiết cho dự án .NET.
Điều hướng vào thư mục Backend:
Bash
cd backend
Khôi phục Gói NuGet: Sử dụng lệnh sau để tải xuống và khôi phục tất cả các gói NuGet đã khai báo trong tệp .csproj và Solution.
Bash
dotnet restore
Mở dự án: Thành viên có thể mở tệp Solution JavaFlorist.sln (nằm trong thư mục backend/) bằng Visual Studio để bắt đầu code.

Bước 3: Thiết lập Frontend (React)
Mục tiêu là tải xuống các gói Node (dependencies) cần thiết cho dự án React.

Quay lại thư mục gốc và điều hướng vào thư mục Frontend:

Bash

cd ..
cd frontend
Cài đặt Gói NPM: Sử dụng lệnh sau để tải xuống và cài đặt tất cả các gói đã khai báo trong tệp package.json (bao gồm React, ReactDOM, và React Router).

Bash

npm install
Kiểm tra Frontend (Tùy chọn): Thành viên có thể kiểm tra xem frontend có chạy được không:

Bash

npm run dev
Sau khi hoàn thành các bước này, tất cả các thành viên trong nhóm sẽ có một môi trường làm việc giống hệt nhau, sẵn sàng để bắt đầu thêm chức năng vào dự án JavaFlorist.Api và frontend.

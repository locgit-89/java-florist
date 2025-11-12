# java-florist:
Hướng dẫn Thiết lập Môi trường cho Thành viên Nhóm
Mỗi thành viên trong nhóm cần thực hiện 3 bước chính: Clone, Thiết lập Backend, và Thiết lập Frontend.

Bước 1: Clone Repository

Lấy URL Clone: các thành viên truy cập vào repo java-florist trên GitHub, sau đó click vào nút < > Code và sao chép URL HTTPS hoặc SSH URL.

Clone về máy: Mở Terminal (hoặc Git Bash) trên máy của họ, điều hướng đến thư mục mà họ muốn lưu trữ dự án (ví dụ: thư mục Projects), và chạy lệnh sau (thay thế URL bằng URL thực tế):

git clone linkCopyTrongMucCode

Bước 2: Thiết lập Backend (ASP.NET Core Web API):

Mục tiêu là khôi phục các gói NuGet (dependencies) cần thiết cho dự án .NET.

Khôi phục Gói NuGet: Sử dụng lệnh sau để tải xuống và khôi phục tất cả các gói NuGet đã khai báo trong tệp .csproj và Solution:

dotnet restore

Mở dự án: Thành viên có thể mở tệp Solution JavaFlorist.sln (nằm trong thư mục backend/) bằng Visual Studio để bắt đầu code.

Bước 3: Thiết lập Frontend (React):

Mục tiêu là tải xuống các gói Node (dependencies) cần thiết cho dự án React.

Cài đặt Gói NPM: Sử dụng lệnh sau để tải xuống và cài đặt tất cả các gói đã khai báo trong tệp package.json (bao gồm React, ReactDOM, và React Router):

npm install

Kiểm tra Frontend (Tùy chọn): Thành viên có thể kiểm tra xem frontend có chạy được không:

npm run dev

Sau khi hoàn thành các bước này, tất cả các thành viên trong nhóm sẽ có một môi trường làm việc giống hệt nhau, sẵn sàng để bắt đầu thêm chức năng vào dự án JavaFlorist.Api và frontend.

LUU Y: moi lần bắt đầu code thi mọi người phải chạy lệnh pull code truoc khi code nhé. moi nguoi se lam nhu sau:
ví dụ đang mở folder backend đê code thi trong terminal cua visual studio chung ta bấm cd .. để lùi 1 cấp thư mục, sau đó chạy lệnh:
git pull
lệnh này sẽ cập nhật code mới về dự án của mình, việc này phải làm thường xuyên mỗi khi code nhé

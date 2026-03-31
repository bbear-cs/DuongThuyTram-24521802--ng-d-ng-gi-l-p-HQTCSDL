# Ứng dụng giả lập hệ quản trị CSDL đơn giản

Đồ án môn **[CS523] Cấu trúc dữ liệu và giải thuật nâng cao**.

## Nội dung
Chương trình mô phỏng một ứng dụng quản lý sinh viên, hỗ trợ các thao tác:
- Thêm sinh viên
- Xóa sinh viên
- Tìm sinh viên theo MSSV
- Tìm sinh viên theo họ tên

## Cấu trúc chương trình
Chương trình được chia thành 3 file chính:
- `khaibao.cpp`: chứa cấu trúc dữ liệu và thuật toán B-Tree
- `giaodien.cpp`: chứa phần giao diện WinAPI và các thao tác từ người dùng
- `main.cpp`: chứa hàm `WinMain()` để khởi động ứng dụng và liên kết các phần của chương trình

## Giao diện
Giao diện được xây dựng bằng **WinAPI**, sử dụng các hàm có sẵn do Windows cung cấp để tạo cửa sổ, ô nhập liệu, nút bấm, vùng hiển thị dữ liệu và vùng hiển thị cây chỉ mục.

## Chức năng chính
- Quản lý danh sách sinh viên
- Hiển thị bảng dữ liệu gốc
- Xây dựng và hiển thị chỉ mục B-Tree bậc 3
- Minh họa thao tác thêm, tìm kiếm và xóa trên B-Tree

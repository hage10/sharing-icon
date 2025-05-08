# Icon Viewer Project

Một ứng dụng đơn giản để xem và tìm kiếm biểu tượng từ các bộ icon khác nhau.

## Tính năng

- Hiển thị biểu tượng từ 3 bộ icon: Iconsax, Infogram, và UI Icon
- Tìm kiếm biểu tượng theo tên
- Giao diện thân thiện với người dùng
- Chức năng chọn biểu tượng và trả về mã icon

## Cách sử dụng

1. Mở file `index.html` trong trình duyệt
2. Chọn tab biểu tượng mong muốn (Iconsax, Infogram, UI Icon)
3. Sử dụng hộp tìm kiếm để lọc biểu tượng
4. Nhấp vào biểu tượng để chọn

## Cấu trúc thư mục

```
icon-project/
│
├── index.html                 # Trang chính của ứng dụng
├── README.md                  # Tệp này
│
├── iconsax/                   # Bộ icon Iconsax
│   ├── style.css              # CSS của Iconsax
│   └── fonts/                 # Font của Iconsax
│       ├── vuesax.svg
│       ├── vuesax.ttf
│       ├── vuesax.woff
│       └── vuesax.eot
│
├── infogram/                  # Bộ icon Infogram
│   ├── css/
│   │   └── style.css          # CSS của Infogram
│   └── fonts/                 # Font của Infogram
│       ├── infogram.svg
│       ├── infogram.ttf
│       ├── infogram.woff
│       └── infogram.eot
│
└── ui-icon/                   # Bộ icon UI Icon
    ├── css/
    │   └── style.css          # CSS của UI Icon
    └── fonts/                 # Font của UI Icon
        ├── uii.svg
        ├── uii.ttf
        ├── uii.woff
        └── uii.eot
```

Ứng dụng giờ đây có thể chạy độc lập mà không cần tham chiếu đến các tệp bên ngoài. 
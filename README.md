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
5. Lắng nghe sự kiện 'ICON_SELECTED'
    ```typescript
    this.messageListener = (event: MessageEvent) => {
      if (event.data && event.data.type === 'ICON_SELECTED') {
        this.iconCode = event.data.iconCode;
      }
    };
    
    window.addEventListener('message', this.messageListener);
    ```
6. Dùng tại giao diện 
    <i class="{iconCode}"></i>

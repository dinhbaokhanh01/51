# Bài tập HTML & CSS tổng hợp

Project gộp các bài thực hành vào một website:

## 1. Menu Dropdown Dọc
- Menu con ẩn mặc định bằng `visibility: hidden`.
- Menu con hiển thị khi rê chuột vào mục cha.
- Sử dụng `position: relative` và `position: absolute`.

## 2. Menu Dropdown Ngang
- Menu nằm theo hàng ngang.
- Menu con ẩn mặc định.
- Hover mục cha để hiển thị menu con.

## 3. Website xem hoạt hình trực tuyến
Có:
- Header cố định bằng `position: fixed`.
- Logo bên trái.
- Head-link/menu điều hướng.
- Left Content: danh sách phim.
- Right Content: khu vực xem video.
- Nhúng video YouTube bằng `<iframe>`.
- Có thẻ `<video>` HTML để minh họa video cục bộ.
- Tìm kiếm phim theo tên.
- Hiệu ứng hover cho liên kết.
- Responsive cho PC, tablet và điện thoại.
- Footer bản quyền.
- Không chèn quảng cáo.

## Cấu trúc

```text
bai-tap-html-css-tong-hop/
├── index.html
├── css/
│   └── style.css
├── videos/
│   └── sample.mp4
└── README.md
```

## Chạy

Mở `index.html` bằng trình duyệt.

Lưu ý: `videos/sample.mp4` là file tùy chọn. Nếu chưa có video local, phần `<video>` sẽ hiện thông báo không tìm thấy video, trong khi phần YouTube iframe vẫn hoạt động.

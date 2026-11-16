# cse122-2551271201 — Bài tập HTML5 Cơ bản & Thẻ Ngữ Nghĩa

## Cấu trúc thư mục

```
.
├── bai02/
│   ├── index.html
│   └── Anh/Bai02/greatwall.jpg
├── ex02/
│   ├── index.html
│   └── Anh/Bai02/greatwall.jpg
├── bai03/
│   ├── index.html
│   └── Anh/Bai03/vinh-ha-long.jpg
└── ex03/
    ├── index.html
    └── Anh/Bai03/vinh-ha-long.jpg
```

## Bài 02 — Quảng cáo tour du lịch "Hành trình Trung Hoa"

- `linear-gradient(160deg, #C9A227, #A8861B)` — nền vàng mù tạt chuyển sắc cho khung quảng cáo.
- `text-shadow` — chữ tiêu đề đổ bóng nhẹ để nổi bật trên nền vàng.
- `text-align: justify` — căn đều hai lề cho các đoạn văn.
- `float: right` — ảnh Vạn Lý Trường Thành nổi bên phải, viền trắng `rgba(255,255,255,0.85)`, `border-radius: 4px`, `margin: 0 0 14px 14px`.
- `@media (max-width: 600px)` — ảnh chuyển về giữa trang trên màn hình nhỏ.

## Bài 03 — Trang giới thiệu Di sản Vịnh Hạ Long

- `linear-gradient(180deg, #7ec8e3, #0a5c8a)` — dải màu xanh biển chuyển sắc cho toàn trang.
- `border-radius: 10px` + `rgba(255,255,255,0.95)` — khung bài viết là thẻ trắng bo góc, đổ bóng sâu.
- Hộp dẫn nhập (Sapo) `#0b3d5c`, chữ trắng in nghiêng, bo góc 6px.
- `::first-letter` — chữ cái đầu mỗi đoạn thân bài phóng to 3rem, màu `#0b3d5c`, `float: left`, `line-height: 0.85` theo phong cách báo chí (Drop Cap).
- `float: right` — ảnh Vịnh Hạ Long nổi bên phải, cạnh hai đoạn thân bài.
- `@media (max-width: 640px)` — ảnh xuống giữa trang trên màn hình nhỏ.

## Xem thử

Mở `bai02/index.html` hoặc `bai03/index.html` bằng trình duyệt, hoặc dùng GitHub Pages:
`https://<username>.github.io/cse122-2551271201/bai03/`

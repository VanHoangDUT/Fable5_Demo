# Fable 5 · DEMO

Bộ demo dùng **Claude Fable 5**. Tất cả là **HTML/CSS/JS thuần** (vanilla),
không framework, không build step. Mở thẳng `index.html` bằng Chrome/Edge là chạy được ngay.

## Mở showcase

Double-click `index.html` ở thư mục gốc để mở trang showcase (có tab chuyển giữa 4 demo), hoặc serve qua HTTP:

```
python -m http.server 8000
# rồi mở http://localhost:8000
```

## 4 demo

| Demo | Thư mục | Mô tả |
|---|---|---|
| **macOS Web** | [`macos/`](macos/) | Clone giao diện macOS Sequoia chạy 100% trong browser: menu bar, dock magnification, window manager, 4 app thật (Calculator, Notes, Terminal, System Settings). Icon và wallpaper là SVG vẽ tay inline. |
| **NEON RUSH** | [`neon-rush/`](neon-rush/) | Game arcade neon trong 1 file `index.html`. |
| **Mô phỏng Thiên hà** | [`galaxy/`](galaxy/) | Mô phỏng thiên hà / hệ hạt trong 1 file `index.html`. |
| **Sổ Chi Tiêu** | [`expense/`](expense/) | App ghi chi tiêu, parser nhập liệu tự nhiên, lưu bằng `localStorage`. |

Mỗi demo đều mở độc lập được (`<demo>/index.html`). Chi tiết từng demo xem README trong thư mục tương ứng.

🍎🍎🍎🍎🍎

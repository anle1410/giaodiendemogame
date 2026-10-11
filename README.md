# 🎮 GAMELAND — Bước vào kỷ nguyên game đa vũ trụ

<div align="center">

### **Không chỉ chơi game. Hãy sống trong một thế giới game kết nối.**

Website giới thiệu trải nghiệm gaming thế hệ mới với video nền, chuyển động điện ảnh  
và hệ sinh thái đa nền tảng lấy cảm hứng từ Web2, Web3 và metaverse.

<br>

**[▶ Mở trang chủ](./index.html)** &nbsp;•&nbsp; **[✉ Liên hệ](mailto:team@example.com)**

</div>

---

## ✨ Giới thiệu

Đây là landing page quảng bá một vũ trụ game đa nền tảng. Trang kết hợp hình ảnh giàu tính điện ảnh, video giới thiệu và các hiệu ứng chuyển động để dẫn dắt người xem qua câu chuyện, sản phẩm và lời mời tham gia cộng đồng.

Tên **GAMELAND**, **LANDGAME** và **Zentry** xuất hiện ở những vị trí khác nhau trong giao diện hiện tại. Nội dung giới thiệu tập trung vào Zentry; tên thương hiệu ở header và footer được giữ nguyên theo thiết kế của trang.

## 🚀 Điểm nổi bật

- **Mở đầu sống động:** màn hình chờ tải, video hero và video xem trước để khám phá cảnh tiếp theo.
- **Chuyển động giàu cảm xúc:** tiêu đề động, hiệu ứng mở rộng mặt nạ hình ảnh, nghiêng thẻ và tương tác trang trí theo chuột.
- **Thiết kế đa thiết bị:** hình ảnh WebP có biến thể dành cho màn hình nhỏ, màn hình trung bình và màn hình lớn.
- **Điều hướng tiện lợi:** thanh điều hướng, menu thu gọn trên màn hình nhỏ, nút xem trailer và lời kêu gọi liên hệ.
- **Âm thanh tùy chọn:** trình phát nhạc nền lặp lại cùng nút bật/tắt âm thanh.
- **Nội dung có cấu trúc:** giới thiệu thế giới, các sản phẩm, câu chuyện và khu vực kết nối.

## 🧭 Nội dung website

| Khu vực | Nội dung |
| --- | --- |
| **Header & điều hướng** | Logo GAMELAND, nút Product và các liên kết Nexus, Vault, Prologue, About, Contacts; có điều khiển âm thanh và menu. |
| **Preloader** | Nhận diện GAMELAND, thanh tiến trình và trạng thái khởi chạy lớp Metagame. |
| **Hero — Redefine Gaming** | Video nền, video kế tiếp, thông điệp “Enter the Metagame Layer — Unleash the Play Economy” và nút xem trailer. |
| **About — Welcome to Zentry** | Giới thiệu một cuộc phiêu lưu MMORPG chung, kết nối người chơi từ nhiều trò chơi và nền tảng. |
| **Discover — Into the Metagame Layer** | Trình bày hệ sinh thái và các trải nghiệm: **RADIANT** (ứng dụng metagame đa nền tảng), **Zigma** (bộ sưu tập NFT lấy cảm hứng từ anime và game), **Nexus** (không gian cộng đồng được game hóa), **Azul** (AI Agent hỗ trợ trải nghiệm chơi game), video xem trước và thông điệp “More Coming Soon!”. |
| **Story — The story of a hidden realm** | Khu vực kể chuyện về thế giới IP đa vũ trụ, đi kèm hình ảnh cổng vào. |
| **Call to action — Join Zentry** | Lời mời cùng xây dựng kỷ nguyên game mới và nút liên hệ. |
| **Footer** | Bản quyền LANDGAME © 2025, liên kết mạng xã hội Dribbble/GitHub/Discord và Privacy Policy. |

## 🛠️ Chạy dự án

Đây là website tĩnh đã có sẵn HTML, CSS và JavaScript được đóng gói; không cần cài dependency để xem trang. Nên chạy qua một máy chủ HTTP cục bộ để các module JavaScript và tài nguyên hoạt động ổn định.

### Cách 1: VS Code Live Server

1. Mở thư mục dự án trong VS Code.
2. Cài extension **Live Server** nếu máy chưa có.
3. Nhấp phải vào [index.html](./index.html) và chọn **Open with Live Server**.

### Cách 2: Python

Mở PowerShell tại thư mục dự án và chạy:

```powershell
python -m http.server 5500
```

Sau đó truy cập **http://localhost:5500**.

> Nếu video hoặc âm thanh không tự phát, hãy kiểm tra cài đặt autoplay của trình duyệt. Video nền được khai báo muted; nhạc nền được cung cấp bằng điều khiển âm thanh trên trang.

## 📁 Cấu trúc thư mục

```text
.
├── index.html             # Cấu trúc và nội dung landing page
├── css/
│   ├── index.min.css      # CSS đã đóng gói
│   └── dev/               # Tài nguyên CSS bổ sung
├── js/
│   ├── index.min.js       # JavaScript đã đóng gói
│   └── dev/               # Tài nguyên JavaScript bổ sung
├── assets/
│   ├── fonts/             # Font chữ cục bộ
│   └── img/               # Hình ảnh, favicon và ảnh responsive
└── files/
    ├── hero-*.mp4         # Video hero
    ├── feature-*.mp4      # Video các thẻ khám phá
    └── music.mp3          # Nhạc nền
```

## ⚙️ Công nghệ & tài nguyên

- HTML5 với các phần tử semantic như `header`, `main`, `section` và `footer`.
- CSS và JavaScript đã build/minify, được tải từ `css/index.min.css` và `js/index.min.js`.
- GSAP được nhắc đến trong tiêu đề trang; các hiệu ứng hoạt họa được triển khai trong bundle JavaScript.
- Video MP4, âm thanh MP3, hình ảnh WebP và font cục bộ nằm trong `files/` và `assets/`.

## 📝 Ghi chú

- Các liên kết điều hướng/mạng xã hội hiện dùng `#`; hãy thay bằng URL thật trước khi phát hành.
- Nút liên hệ đang trỏ tới địa chỉ mẫu `team@example.com`; cần cập nhật thành email chính thức.
- Trang tải bundle trực tiếp, không kèm mã nguồn phát triển hay cấu hình build trong thư mục hiện tại. Vì vậy, hãy chỉnh sửa quy trình build gốc nếu cần tái tạo bundle thay vì sửa trực tiếp file minify.
- Nội dung và hình ảnh tập trung vào trải nghiệm trình diễn; nên kiểm tra chính sách autoplay, tải video và hiệu năng trên thiết bị mục tiêu trước khi triển khai công khai.

## 👤 Tác giả

**Lê Phú An**

---

<div align="center">

### **ENTER THE METAGAME. REDEFINE GAMING.**

*Một thế giới — vô vàn cuộc phiêu lưu.*

</div>

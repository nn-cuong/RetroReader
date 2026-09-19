# RetroReader

**RetroReader** là ứng dụng đọc sách và truyện tranh all-in-one cao cấp dành cho máy chơi game cầm tay **TrimUI Brick Pro (TG4040)**, kết hợp trọn vẹn sức mạnh của cả hai ứng dụng đọc sách chữ (**RetroBooks**) và truyện tranh (**RetroComics**).

---

## 📥 Tải về & Cài đặt (Download & Installation)
* **Tải bản phát hành:** [RetroReader v1.2 Releases](https://github.com/nn-cuong/RetroReader/releases/tag/v1.2)
* **Cách cài đặt:**
  1. Tải file zip `RetroReader.v1.2.zip` từ đường dẫn trên.
  2. Giải nén và sao chép thư mục `RetroReader` vào thư mục `Apps/` trên thẻ nhớ SD (đường dẫn: `/mnt/SDCARD/Apps/RetroReader`).
  3. Cắm thẻ nhớ vào máy TrimUI Brick Pro, mở mục **Apps** và khởi chạy **RetroReader**.

---

## 🌟 Tính năng nổi bật

* **Hỗ trợ các định dạng đọc sách & truyện tranh chuyên nghiệp:**
  * 🎨 **Truyện tranh & Manga:** `.cbz`, `.cbr`
  * 📄 **Tài liệu:** `.pdf` (kết xuất trang chất lượng cao qua MuPDF)
  * 📚 **Sách điện tử Ebook:** `.epub`
  * 📱 **Sách Amazon Kindle:** `.mobi`, `.azw`, `.azw3`
* **Bộ điều hướng thông minh (Smart Dispatcher):** Tự động nhận diện định dạng tệp để mở đúng trình đọc:
  * File truyện/PDF: Mở **Comic Engine** (lật trang ảnh, phóng to zoom/pan, xoay 4 hướng).
  * File sách chữ/ebook: Mở **Flow Text Engine** (ngắt dòng chữ, đổi cỡ chữ L/R, nhảy mục lục chương TOC).

* **Bảng màu 8 chủ đề êm mắt:**
  * Paper (mặc định), Vintage Dark, Warm Night, AMOLED Black, Forest, Coastal Earth, Gruvbox, Nordic Frost.
  * Màu nền ô đang chọn (`sel_bg`) được thiết kế sáng nhẹ hơn nền 1 tông, mang lại cảm giác dễ chịu khi đọc trong đêm.
* **Popup thoát an toàn chống treo máy**.

---

## 🎮 Hướng dẫn điều khiển

### 1. Tại Thư viện (Library)
* **DPAD / Joystick:** Di chuyển chọn sách / thư mục.
* **L / R:** Chuyển đổi qua lại giữa các tab (Thư viện / Yêu thích / Flashcards).
* **L2 / R2:** Đổi chủ đề màu sắc (Theme).
* **Nút A:** Mở sách / truyện (hoặc vào thư mục).
* **Nút B:** Chuyển đổi qua lại giữa chế độ **Lưới (Grid View)** và **Danh sách (List View)**.
* **Nút X:** Đánh dấu hoặc bỏ đánh dấu Yêu thích (Favorite).
* **Nút Y:** Mở bộ lọc định dạng sách (Filter).
* **SELECT:** Xem thông tin chi tiết sách.
* **START:** Mở popup thoát ứng dụng (A: Thoát, B: Hủy).

### 2. Khi đọc Truyện tranh & PDF (Comic Engine)
* **R2:** Chuyển đổi chế độ đọc (**Mode 0: Single Page** lật từng trang $\longleftrightarrow$ **Mode 1: Webtoon** cuộn dọc liên tục mượt mà kèm cơ chế nạp trước 3 trang dưới).
* **DPAD Trái/Phải hoặc L1/R1:** Lật trang trước/sau (Mode Single) hoặc Nhảy 1 màn hình / trang (Mode Webtoon).
* **DPAD Lên/Xuống & Joystick Trái:** Cuộn đọc mượt mà 60 FPS từ trên xuống dưới (Mode Webtoon) hoặc di chuyển góc nhìn ảnh khi phóng to (Mode Single).
* **Joystick Phải:** Lướt nhanh nhiều trang.
* **L2:** Mở giao diện chọn trang nhanh dạng lưới ảnh thu nhỏ (Page Select / Thumbnail Grid).
* **Nút A:** Bật / tắt thanh trạng thái HUD.
* **Nút Y:** Phóng to (Zoom In: Fit $\rightarrow$ 150% $\rightarrow$ 200% $\rightarrow$ 250%).
* **Nút B:** Trở về kích thước vừa màn hình (Fit to Screen).
* **Nút X:** Xoay màn hình 90° (hỗ trợ đọc truyện dạng dọc hoặc ngang).
* **SELECT:** Lưu tiến trình đọc và quay về Thư viện.

### 3. Khi đọc Sách chữ & Ebook (Flow Text Engine)
* **DPAD Lên/Xuống hoặc Joystick:** Cuộn dòng đọc mượt mà.
* **L1 / R1:** Nhảy trang tiếp theo.
* **L2:** Mở Mục lục chương (TOC) để nhảy nhanh.
* **Nút B:** Bật chế độ Flashcard (Cursor mode) để chọn và lưu trích dẫn/từ vựng vào Flashcard.
* **Nút A:** Bật/Tắt thanh trạng thái (HUD).
* **Nút X:** Xoay màn hình 90°.
* **Nút Y:** Đổi chủ đề màu nền khi đọc.
* **SELECT:** Lưu tiến trình đọc và quay về Thư viện.

### 4. Tab Flashcards (Thư viện thẻ trích dẫn)
* **DPAD Lên/Xuống:** Di chuyển chọn giữa các thẻ flashcard đã lưu.
* **Nút A:** Mở xem chi tiết thẻ (toàn bộ nội dung trích dẫn, tên sách, chương, số trang, ngày lưu).
* **Nút X:** Xóa flashcard (kèm popup xác nhận an toàn: A: Đồng ý xóa, B: Hủy).
* **Khi xem chi tiết thẻ:**
  * **DPAD:** Cuộn đọc nội dung trích dẫn dài.
  * **Nút Y:** Nhảy thẳng vào sách ngay tại vị trí trích dẫn đó.
  * **Nút X:** Xóa thẻ (có popup xác nhận an toàn).
  * **Nút B:** Đóng xem chi tiết.

---

## ⚡ Quản lý Xung nhịp & Tiết kiệm Pin (CPU Governor & Power Saving)
* **Khóa trần xung nhịp thông minh:** Tự động giới hạn dải tần hoạt động của CPU ở mức **408MHz – 1008MHz (1.0GHz)** thông qua `sysfs` khi khởi động app, ngăn chặn hệ thống boost xung nhịp ảo lên 1800MHz - 2000MHz. Khi vào chế độ đọc truyện/sách nâng cao tự động điều tiết lên **1200MHz**.
* **Cơ chế khôi phục tự động (Safe CPU Restore):** Khi thoát ứng dụng, hệ thống tự động trả lại trần 1800MHz (dải chuẩn 1008MHz - 1800MHz) và bật lại 4 core cho Menu chính.
* **Điều phối nghỉ động (Dynamic Sleep Scheduler):**
  * Chạy **60 FPS (16ms)** khi người dùng tương tác, lật trang, cuộn analog hoặc hiệu ứng chữ chạy marquee.
  * Chuyển sang chế độ nghỉ sâu **30 FPS (32ms)** khi người dùng dừng lại đọc sách tĩnh, giúp máy luôn mát mẻ và tối đa hóa thời lượng pin.

---

## 👨‍💻 Tác giả (Author)
* **Nguyễn Ngọc Cường** (nn.cuong.404@gmail.com)
* **Facebook:** aegony98 | **Instagram:** ich_heisse_cuong | **GitHub:** github.com/nn-cuong

---

## ☕ Ủng hộ phát triển (Donate)
Nếu các bạn thích sản phẩm này, hãy ủng hộ nhà phát triển tại:
* **Vietcombank:** `cuongnguyen98`
* **TPBank:** `6119 8128 888`

Cảm ơn các bạn.



# RetroReader

<p align="center">
  <a href="#-tiếng-việt"><b>Tiếng Việt</b></a> •
  <a href="#-english"><b>English</b></a>
</p>

---

## 🇻🇳 Tiếng Việt

**RetroReader** là ứng dụng đọc sách và truyện tranh all-in-one cao cấp dành cho máy chơi game cầm tay **TrimUI Brick Pro (TG4040)**, kết hợp trọn vẹn sức mạnh của cả hai ứng dụng đọc sách chữ (**RetroBooks**) và truyện tranh (**RetroComics**).

### 📥 Tải về & Cài đặt (Download & Installation)
* **Tải bản phát hành:** [RetroReader v1.3 Releases](https://github.com/nn-cuong/RetroReader/releases/tag/v1.3)
* **Cách cài đặt:**
  1. **Xoá toàn bộ phiên bản cũ:** Nếu trên thẻ nhớ đã có thư mục `RetroReader` cũ trong `Apps/` (đường dẫn: `/mnt/SDCARD/Apps/RetroReader`), hãy xóa hoàn toàn thư mục này để tránh xung đột file cấu hình hoặc thư viện cũ.
  2. Tải file zip `RetroReader.v1.3.zip` từ đường dẫn trên.
  3. Giải nén và sao chép thư mục `RetroReader` mới vào thư mục `Apps/` trên thẻ nhớ SD (đường dẫn: `/mnt/SDCARD/Apps/RetroReader`).
  4. Cắm thẻ nhớ vào máy TrimUI Brick Pro, mở mục **Apps** và khởi chạy **RetroReader**.

### 📁 Chép các định dạng vào Books trên thẻ nhớ
Sau khi cài đặt ứng dụng, toàn bộ tài liệu, sách báo và truyện tranh cần được chép vào thư mục **`Books`** ngay tại thư mục gốc của thẻ nhớ SD:
* **Đường dẫn trên thẻ nhớ:** `SD:/Books/` (khi máy TrimUI nhận diện là `/mnt/SDCARD/Books`).
* **Hỗ trợ sắp xếp thư mục phân cấp:** Bạn có thể tự do tạo các thư mục con tùy ý bên trong `Books/` để phân loại theo sở thích (ví dụ: `Books/Manga/`, `Books/Light Novel/`, `Books/Kinh tế/`, `Books/Tác giả/...`). RetroReader hỗ trợ duyệt cây thư mục không giới hạn độ sâu.
* **Các định dạng tệp được hỗ trợ đầy đủ:**
  * 🎨 **Truyện tranh & Manga:** `.cbz`, `.cbr`, `.zip`
  * 📄 **Tài liệu & Tạp chí:** `.pdf` (kết xuất trang vector độ nét cao)
  * 📚 **Sách điện tử Ebook:** `.epub`
  * 📱 **Sách Amazon Kindle:** `.mobi`, `.azw`, `.azw3`

> **Lưu ý:** RetroReader tự động quét và nhận diện bìa sách (Cover), nạp trước thông minh và ghi nhớ vị trí đọc riêng biệt cho từng cuốn sách trong thư mục này.

### 🌟 Tính năng nổi bật

* **Hỗ trợ các định dạng đọc sách & truyện tranh chuyên nghiệp:**
  * 🎨 **Truyện tranh & Manga:** `.cbz` (hỗ trợ giải mã WebP gốc), `.cbr`, `.zip`
  * 📄 **Tài liệu:** `.pdf` (kết xuất trang chất lượng cao qua MuPDF)
  * 📚 **Sách điện tử Ebook:** `.epub`
  * 📱 **Sách Amazon Kindle:** `.mobi`, `.azw`, `.azw3`
* **Bộ điều hướng thông minh (Smart Dispatcher):** Tự động nhận diện định dạng tệp để mở đúng trình đọc:
  * File truyện/ảnh/PDF: Mở **Comic Engine** (lật trang ảnh, Webtoon cuộn mượt 60 FPS, phóng to zoom/pan, xoay 4 hướng).
  * File sách chữ/ebook: Mở **Flow Text Engine** (ngắt dòng chữ thông minh, căn đều 2 bên, tùy biến font/size/spacing, nhảy mục lục chương TOC phân cấp thụt lề, lưu Flashcard).
* **Bảng màu 8 chủ đề êm mắt:**
  * Paper (mặc định), Vintage Dark, Warm Night, AMOLED Black, Forest, Coastal Earth, Gruvbox, Nordic Frost.
  * Màu nền ô đang chọn (`sel_bg`) được thiết kế sáng nhẹ hơn nền 1 tông, mang lại cảm giác dễ chịu khi đọc trong đêm.
* **Popup thoát an toàn chống treo máy:** Xác nhận thoát êm ái, khôi phục xung nhịp CPU gốc.

### 🎮 Hướng dẫn điều khiển các nút bấm

#### 1. Tại Thư viện (Library Browser)
* **DPAD / Joystick Trái:** Di chuyển chọn sách / vào thư mục.
* **L1 / R1:** Chuyển đổi qua lại giữa các tab (**Thư viện** $\longleftrightarrow$ **Yêu thích** $\longleftrightarrow$ **Flashcards**).
* **L2 / R2:** Đổi bảng màu chủ đề (Theme).
* **Nút A:** Mở sách / truyện (hoặc mở thư mục con).
* **Nút B:** Chuyển đổi qua lại giữa chế độ hiển thị **Lưới bìa (Grid View)** và **Danh sách (List View)**.
* **Nút X:** Đánh dấu thêm vào hoặc bỏ khỏi mục **Yêu thích (Favorite)**.
* **Nút Y:** Mở hộp thoại **Bộ lọc định dạng (Format Filter)** để lọc nhanh theo EPUB, CBZ, CBR, PDF, MOBI, TXT...
* **SELECT:** Xem thông tin chi tiết / siêu dữ liệu của cuốn sách (About / Metadata).
* **START:** Mở hộp thoại xác nhận thoát an toàn khỏi ứng dụng (Nút A: Thoát, Nút B: Hủy).

#### 2. Khi đọc Truyện tranh & PDF (Comic Engine)
* **R2:** Chuyển đổi chế độ đọc:
  * **Single Page (Mode 0):** Lật từng trang truyền thống.
  * **Webtoon (Mode 1):** Cuộn dọc liên tục mượt mà 60 FPS kèm cơ chế nạp trước thông minh 3 trang tiếp theo.
* **DPAD Trái / Phải hoặc L1 / R1:**
  * *Chế độ Single:* Lật sang trang trước / trang kế tiếp.
  * *Chế độ Webtoon:* Nhảy cuộn nhanh 1 trang màn hình lên hoặc xuống.
* **DPAD Lên / Xuống & Joystick Trái:**
  * *Chế độ Webtoon:* Cuộn đọc mượt mà 60 FPS từ trên xuống dưới.
  * *Chế độ Single:* Di chuyển góc nhìn (Pan ảnh) khi đang phóng to Zoom.
* **Joystick Phải:** Thu phóng (Zoom in / Zoom out).
* **L2:** Mở giao diện chọn trang nhanh dạng lưới ảnh thu nhỏ (**Thumbnail Grid / Page Select**).
* **Nút A:** Bật / tắt thanh trạng thái (HUD: hiển thị pin, đồng hồ, % trang, tên file).
* **Nút Y:** Phóng to ảnh (Zoom In theo các nấc: Fit $\rightarrow$ 150% $\rightarrow$ 200% $\rightarrow$ 250%).
* **Nút B:** Thu nhỏ / Đưa ảnh trở về kích thước vừa vặn màn hình (Fit to Screen).
* **Nút X:** Xoay màn hình 90° (hỗ trợ đọc xoay dọc / xoay ngang thuận tiện).
* **SELECT:** Lưu tiến trình đọc hiện tại và quay trở về Thư viện sách.

#### 3. Khi đọc Sách chữ & Ebook (Flow Text Engine)
* **DPAD Lên / Xuống hoặc Joystick Trái:** Cuộn dòng đọc mượt mà từng dòng.
* **L1 / R1:** Nhảy trang trước / lật trang sau nhanh chóng.
* **L2:** Mở **Mục lục chương (TOC)** để nhảy nhanh đến chương mong muốn (hỗ trợ hiển thị phân cấp thụt lề nhiều cấp).
* **R2:** Mở menu tùy biến hiển thị **Typography** (điều chỉnh trực quan: cỡ chữ, giãn dòng, giãn đoạn, khoảng cách từ, độ rộng lề 2 bên, căn đều lề Justify, bảng màu đọc).
* **Nút B:** Bật chế độ con trỏ trích dẫn (**Flashcard Cursor mode**) để bôi đen đoạn văn/từ vựng và lưu vào thẻ ghi nhớ Flashcard.
* **Nút A:** Bật / tắt thanh trạng thái hiển thị (HUD: tiến độ %, pin, giờ, chương hiện tại).
* **Nút X:** Xoay màn hình hiển thị 90°.
* **Nút Y:** Đổi nhanh bảng màu nền khi đọc sách.
* **SELECT:** Tự động lưu tiến trình đọc và quay về Thư viện sách.

#### 4. Tab Flashcards & Hộp thoại chi tiết thẻ
* **Tại danh sách thẻ trích dẫn:**
  * **DPAD Lên / Xuống:** Chọn giữa các thẻ ghi nhớ đã lưu.
  * **Nút A:** Mở xem toàn bộ nội dung chi tiết của thẻ (trích dẫn đầy đủ, tên sách, chương, số trang, ngày lưu).
  * **Nút X:** Xóa flashcard (kèm popup xác nhận an toàn).
* **Khi đang mở hộp thoại chi tiết thẻ:**
  * **DPAD Lên / Xuống hoặc L1 / R1:** Cuộn đọc nội dung trích dẫn dài.
  * **Nút Y:** Nhảy trực tiếp vào cuốn sách ngay tại đúng vị trí trích dẫn đó.
  * **Nút X:** Xóa thẻ flashcard này.
  * **Nút B hoặc SELECT:** Đóng hộp thoại xem chi tiết.

### ⚡ Quản lý Xung nhịp & Tiết kiệm Pin (CPU Governor & Power Saving)
* **Khóa trần xung nhịp thông minh:** Tự động giới hạn dải tần hoạt động của CPU ở mức **408MHz – 1008MHz (1.0GHz)** thông qua `sysfs` khi khởi động app, ngăn chặn hệ thống boost xung nhịp ảo lên 1800MHz - 2000MHz. Khi vào chế độ đọc truyện/sách nâng cao tự động điều tiết lên **1200MHz**.
* **Điều phối nghỉ động (Dynamic Sleep Scheduler):**
  * Chạy **60 FPS (16ms)** khi người dùng tương tác, lật trang, cuộn analog hoặc hiệu ứng chữ chạy marquee.
  * Chuyển sang chế độ nghỉ sâu **30 FPS (32ms)** khi người dùng dừng lại đọc sách tĩnh, giúp máy luôn mát mẻ và tối đa hóa thời lượng pin.

### 👨‍💻 Tác giả (Author)
* **Nguyễn Ngọc Cường** (nn.cuong.404@gmail.com)
* **Facebook:** aegony98 | **Instagram:** ich_heisse_cuong | **GitHub:** github.com/nn-cuong

### ☕ Ủng hộ phát triển (Donate)
Nếu các bạn thích sản phẩm này, hãy ủng hộ nhà phát triển tại:
* **Vietcombank:** `cuongnguyen98`
* **TPBank:** `6119 8128 888`

Cảm ơn các bạn.

---

## 🇬🇧 English

**RetroReader** is an all-in-one premium ebook and manga reader designed for the **TrimUI Brick Pro (TG4040)** handheld gaming console, seamlessly merging the power of both **RetroBooks** (flow-text) and **RetroComics** (graphics engine).

### 📥 Download & Installation
* **Download Releases:** [RetroReader v1.3 Releases](https://github.com/nn-cuong/RetroReader/releases/tag/v1.3)
* **Installation Steps:**
  1. **Delete all previous versions:** If you already have an older `RetroReader` folder inside `Apps/` on your SD card (path: `/mnt/SDCARD/Apps/RetroReader`), completely delete it first to avoid conflicts with legacy configuration or library files.
  2. Download `RetroReader.v1.3.zip` from the release link above.
  3. Extract and copy the fresh `RetroReader` folder into the `Apps/` directory on your SD card (path: `/mnt/SDCARD/Apps/RetroReader`).
  4. Insert the SD card into your TrimUI Brick Pro, navigate to **Apps**, and launch **RetroReader**.

### 📁 Copying Formats into Books Folder on SD Card
After installing the application, all books, manga, and reading documents should be placed inside the **`Books`** directory at the root of your SD card:
* **Path on SD Card:** `SD:/Books/` (mounted as `/mnt/SDCARD/Books` on the device).
* **Nested Subdirectories Supported:** You can freely organize your library into subfolders (e.g., `Books/Manga/`, `Books/Light Novels/`, `Books/Fiction/`, `Books/Authors/...`). RetroReader supports infinite nested directory tree browsing.
* **Fully Supported Formats:**
  * 🎨 **Comics & Manga:** `.cbz`, `.cbr`, `.zip`
  * 📄 **Documents & Magazines:** `.pdf` (high-fidelity vector rendering via MuPDF)
  * 📚 **Ebooks:** `.epub`
  * 📱 **Amazon Kindle Books:** `.mobi`, `.azw`, `.azw3`

> **Note:** RetroReader automatically scans and caches covers, performs predictive preheating, and tracks per-book reading progress seamlessly.

### 🌟 Key Highlights
* **Comprehensive Format Support:**
  * 🎨 **Comics & Manga:** `.cbz` (supports native WebP), `.cbr`, `.zip`
  * 📄 **Documents:** `.pdf` (high-quality page rendering via MuPDF)
  * 📚 **Ebooks:** `.epub`
  * 📱 **Amazon Kindle:** `.mobi`, `.azw`, `.azw3`
* **Smart Engine Dispatcher:** Automatically detects file types to route them into the proper engine:
  * Comics & PDFs: Launches **Comic Engine** (single page flip, 60 FPS Webtoon vertical scrolling, zoom/pan, 4-way rotation).
  * Ebooks & Text files: Launches **Flow Text Engine** (dynamic word wrapping, text justification, customizable fonts/sizes/margins, multi-level TOC navigation, flashcards).
* **8 Eye-Friendly Reading Themes:**
  * Paper (Default), Vintage Dark, Warm Night, AMOLED Black, Forest, Coastal Earth, Gruvbox, Nordic Frost.
  * Selection highlight (`sel_bg`) is tuned one shade brighter than the background for comfortable night-time reading.
* **Zero-Freeze Safe Exit Modal:** Double-bordered 3D popup preventing device freezes and safely restoring CPU governor profiles.

### 🎮 Controls Guide

#### 1. Library (File Browser)
* **DPAD / Left Joystick:** Navigate books & folders.
* **L1 / R1:** Switch tabs (`Library` $\longleftrightarrow$ `Favorites` $\longleftrightarrow$ `Flashcards`).
* **L2 / R2:** Cycle color themes.
* **Button A:** Open book/comic (or enter subdirectory).
* **Button B:** Toggle view modes (**Grid View** $\longleftrightarrow$ **List View**).
* **Button X:** Add or remove Favorite.
* **Button Y:** Open format filter dialog (filter by EPUB, CBZ, CBR, PDF, MOBI, TXT...).
* **SELECT:** View book metadata & file details (About dialog).
* **START:** Open safe exit dialog (Button A: Exit, Button B: Cancel).

#### 2. Comics & PDFs (Comic Engine)
* **R2:** Switch reading modes:
  * **Single Page (Mode 0):** Traditional page flip.
  * **Webtoon (Mode 1):** Continuous 60 FPS vertical scroll with 3-page lookahead preloading.
* **DPAD Left/Right or L1/R1:**
  * *Single mode:* Previous / Next page.
  * *Webtoon mode:* Jump 1 screen / page up or down.
* **DPAD Up/Down & Left Joystick:**
  * *Webtoon mode:* Smooth 60 FPS vertical scrolling.
  * *Single mode:* Pan viewport when zoomed in.
* **Right Joystick:** Zoom (Zoom in / Zoom out).
* **L2:** Open quick thumbnail grid (**Page Select / Thumbnail Grid**).
* **Button A:** Toggle on-screen HUD (time, battery, page %, filename).
* **Button Y:** Zoom In (Fit $\rightarrow$ 150% $\rightarrow$ 200% $\rightarrow$ 250%).
* **Button B:** Reset zoom to Fit to Screen.
* **Button X:** Rotate screen 90° (supports portrait and landscape reading).
* **SELECT:** Save reading progress and return to Library.

#### 3. Ebooks & Text Books (Flow Text Engine)
* **DPAD Up/Down or Left Joystick:** Smooth line-by-line scrolling.
* **L1 / R1:** Jump to previous / next page.
* **L2:** Open Table of Contents (**TOC**) with multi-level indentation for quick chapter jumping.
* **R2:** Open **Typography Menu** (adjust font size, line spacing, paragraph spacing, word spacing, side margins, text justification, reading theme).
* **Button B:** Toggle **Flashcard Cursor Mode** to highlight text and save quotes to flashcards.
* **Button A:** Toggle on-screen HUD (reading progress %, battery, clock, current chapter).
* **Button X:** Rotate screen 90°.
* **Button Y:** Cycle reading background themes.
* **SELECT:** Save progress and return to Library.

#### 4. Flashcards Tab & Detail Modal
* **In Flashcards List:**
  * **DPAD Up/Down:** Navigate saved quote cards.
  * **Button A:** View quote card details (full quote text, book title, chapter, page, date).
  * **Button X:** Delete flashcard (with safe confirmation popup).
* **Inside Detail View:**
  * **DPAD Up/Down or L1/R1:** Scroll long quote text.
  * **Button Y:** Jump directly into the book at the exact saved quote location.
  * **Button X:** Delete this quote card.
  * **Button B or SELECT:** Close detail view.

### ⚡ Hardware CPU Governor & Power Saving
* **Smart Frequency Cap:** Automatically restricts CPU operating range to **408MHz – 1008MHz (1.0GHz)** via `sysfs` on startup, preventing unnecessary thermal throttling from artificial boosts to 1800MHz - 2000MHz. Automatically scales to **1200MHz** during intensive comic/manga reading.
* **Dynamic Sleep Scheduler:**
  * Runs at **60 FPS (16ms)** during input, page turns, analog scrolling, or marquee header animation.
  * Drops to deep idle **30 FPS (32ms)** during static reading, keeping the device cool and maximizing battery life.

### 👨‍💻 Author
* **Nguyễn Ngọc Cường** (nn.cuong.404@gmail.com)
* **Facebook:** aegony98 | **Instagram:** ich_heisse_cuong | **GitHub:** github.com/nn-cuong

### ☕ Support Development (Donate)
If you enjoy this app, consider supporting the developer at:
* **Vietcombank:** `cuongnguyen98`
* **TPBank:** `6119 8128 888`

Thank you!

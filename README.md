# number-learning-game
Game học số từ 0 tới 9 cho bé 4 tuổi

## 🎮 Các Phiên Bản Game

Dự án này có 3 phiên bản game với các tính năng khác nhau:

### 1. **game-simple.html** - Phiên bản đơn giản (Khuyên dùng) ⭐
✅ **Tính năng nổi bật:**
- Không cần internet, chạy offline hoàn toàn
- Có nút START/STOP để điều khiển game
- Canvas 2D thuần túy, không cần thư viện ngoài
- Số rơi từ trên xuống với animation mượt mà
- Âm thanh khi bắn trúng và game over
- Giao diện đẹp với gradient tím
- Hiển thị đầy đủ: Máu, Điểm, Số sai, Số trúng
- Nút "Chơi lại" khi game over

**Cách chơi:**
1. Nhấn nút START để bắt đầu
2. Nhấn phím số (0-9) để bắn vào số đang rơi
3. Trúng: Số biến mất + âm thanh + tăng điểm
4. Sai: Trừ điểm
5. Số chạm đáy: Trừ máu
6. Game over khi: Máu = 0 hoặc Sai >= 100 lần
7. Nhấn ESC hoặc nút STOP để tạm dừng

### 2. **index.html** - Phiên bản 3D (Babylon.js)
🎨 **Tính năng:**
- Đồ họa 3D đẹp mắt với Babylon.js engine
- Số rơi xuống dưới dạng sphere 3D
- Camera có thể xoay 360 độ
- Đọc số bằng tiếng Việt khi bắn trúng
- Hiệu ứng ánh sáng và bóng đổ

⚠️ **Lưu ý:** Cần kết nối internet để tải Babylon.js từ CDN

### 3. **game.html** - Phiên bản cổ điển
📝 **Tính năng:**
- Canvas 2D cơ bản
- Điều khiển súng bằng chuột
- Click để bắn
- Đơn giản, dễ hiểu

## 🚀 Cách sử dụng

1. Clone repository này:
```bash
git clone https://github.com/vanantrinh-142857/number-learning-game.git
```

2. Mở file game bằng trình duyệt:
   - **Khuyên dùng:** `game-simple.html` (đầy đủ tính năng, offline)
   - `index.html` (3D, cần internet)
   - `game.html` (cổ điển, đơn giản)

## 📖 Hướng dẫn cho phụ huynh

Game giúp trẻ:
- Học nhận biết số từ 0 đến 9
- Rèn luyện phản xạ và tốc độ
- Tăng khả năng tập trung
- Làm quen với bàn phím số

**Khuyến nghị:** Cho trẻ chơi 10-15 phút mỗi lần để tránh mỏi mắt.

## 🛠️ Công nghệ sử dụng

- **game-simple.html**: HTML5 Canvas 2D, Web Audio API, Pure JavaScript
- **index.html**: Babylon.js 3D Engine, Web Speech API
- **game.html**: HTML5 Canvas 2D, Vanilla JavaScript

## 📝 License

MIT License - Tự do sử dụng cho mục đích giáo dục

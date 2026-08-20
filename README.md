# 🧬 Tế Bào Phiêu Lưu Ký (Cell Cycle Snake Game)

Trò chơi con rắn kết hợp kiến thức sinh học về **Chu Kỳ Tế Bào (Cell Cycle)** và **Nguyên Phân (Mitosis)**, được thiết kế dưới dạng game web HTML5 Canvas thuần (Pure HTML/CSS/JS).

---

## 🔬 Giới Thiệu & Kiến Thức Sinh Học

Trò chơi mô phỏng hành trình phát triển và phân chia của một tế bào qua 4 giai đoạn chính trong chu kỳ tế bào:

`
[🌱 Pha G1: Sinh Trưởng] 
       ⬇ 
[🧬 Pha S: Nhân Đôi ADN] 
       ⬇ 
[⭐ Pha G2: Chuẩn Bị Phân Bào] 
       ⬇ 
[✨ Pha M: Nguyên Phân (Tách Đôi & x2 Điểm)]
`

### 1. 🌱 Pha G1 (Gap 1 - Sinh Trưởng)
- **Nhiệm vụ:** Tế bào lớn lên, gia tăng thể tích và tích lũy năng lượng.
- **Thức ăn:** AA (Acid Amin - Đỏ) và ATP (Năng lượng - Vàng).
- **Mục tiêu:** Thu thập đủ 10 đơn vị dinh dưỡng.

### 2. 🧬 Pha S (Synthesis - Nhân Đôi ADN)
- **Nhiệm vụ:** Tổng hợp và nhân đôi chuỗi xoắn kép ADN theo nguyên tắc bổ sung ( = T$,  \equiv X$).
- **Thức ăn:** Các Nucleotide A, T, G, X nhiều màu sắc.
- **Mục tiêu:** Thu thập đủ 15 Nucleotide.
- **Hiệu ứng:** Rắn phát sáng lấp lánh mô phỏng quá trình nhân đôi nhiễm sắc thể.

### 3. ⭐ Pha G2 (Gap 2 - Chuẩn Bị Phân Bào)
- **Nhiệm vụ:** Tổng hợp Enzyme, protein thoi vô sắc và kiểm tra tính toàn vẹn của ADN.
- **Thức ăn:** Enzyme (★ / E) hình ngôi sao quay tròn.
- **Mục tiêu:** Thu thập đủ 8 Enzyme. Thân rắn dài đòi hỏi kỹ năng điều khiển khéo léo.

### 4. ✨ Pha M (Mitosis - Nguyên Phân)
- **Cutscene:** Hoạt hình tự động mô phỏng tế bào mẹ phân chia thành 2 tế bào con giống hệt nhau ($).
- **Phần thưởng:** Hoàn thành chu kỳ, nhân đôi hệ số điểm (, x4, x8...$), nhận điểm thưởng lớn và bắt đầu chu kỳ mới với tốc độ tăng dần.

---

## 🎮 Cách Chơi & Điều Khiển

| Thao tác | Phím / Hành động |
|---|---|
| **Di chuyển** | ↑ ↓ ← → hoặc W A S D |
| **Chuột** | Nhấp chuột về hướng muốn di chuyển so với đầu rắn |
| **Cảm ứng** | Vuốt màn hình (Swipe) |
| **Tạm dừng / Tiếp tục** | Phím P hoặc Esc (hoặc phím Space) |

---

## 🌟 Tính Năng Nổi Bật

- 🔬 **Sân chơi Kính hiển vi:** Vùng di chuyển hình tròn độc đáo mô phỏng thị trường kính hiển vi sinh học.
- 🎵 **Âm thanh sống động:** Tích hợp nhạc nền và hiệu ứng âm thanh bằng Web Audio API thuần (không cần tải file ngoài).
- 🏆 **Bảng xếp hạng (Leaderboard):** Lưu điểm và lịch sử chu kỳ trên trình duyệt (LocalStorage).
- 📖 **Hướng dẫn chi tiết (Tutorial):** 4 tab giải thích luật chơi, kiến thức sinh học, điều khiển và mẹo chơi.
- 💡 **Thẻ kiến thức chuyển pha:** Pop-up giải thích ngắn gọn, súc tích ý nghĩa sinh học của từng pha khi chuyển tiếp.

---

## 🚀 Hướng Dẫn Chạy Game

Không cần cài đặt bất kỳ thư viện hay server nào:
1. Tải về hoặc clone repository:
   `ash
   git clone https://github.com/chinmt22225-ops/Snake_Biology_Game.git
   `
2. Mở trực tiếp file index.html bằng bất kỳ trình duyệt web hiện đại nào (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari,...).

# 🕹️ FBNeo Retro Emulator (Android)

Một trình giả lập game Arcade/Retro siêu nhẹ dành cho Android, được xây dựng dựa trên lõi **FinalBurn Neo (FBNeo)** cực kỳ ổn định. Dự án tập trung vào trải nghiệm cốt lõi: mượt mà, tối ưu tài nguyên phần cứng và tối đa hóa không gian hiển thị.

## ✨ Tính năng nổi bật

*   **Tương thích hoàn hảo:** Chơi mượt các hệ máy Arcade huyền thoại như NeoGeo, CPS-1, CPS-2, CPS-3 (Bộ đội, Tam Quốc, KOF, Metal Slug...).
*   **Giao diện Tối giản (Ultra-Minimalist UI):** 
    *   Loại bỏ hoàn toàn các chi tiết bo góc rườm rà, sử dụng các module thiết kế vuông vức 100%. 
    *   Navigation và các nút điều khiển sử dụng hệ thống Icon thay cho Text, giúp mở rộng tối đa không gian hiển thị cho game.
*   **Siêu nhẹ & Tối ưu tài nguyên:** Code được thiết kế chuẩn DRY và Clean. Áp dụng các kỹ thuật quản lý bộ nhớ nghiêm ngặt, tự động giải phóng tài nguyên (free memory) liên tục. App chạy nhẹ nhàng trên cả các thiết bị low-power (như các dòng TV Box chạy chip ARM) mà không lo rò rỉ RAM hay giật lag.
*   **👥 Hỗ trợ Multiplayer:** Tích hợp tính năng kết nối chơi nhóm, dễ dàng co-op cùng bạn bè.
*   **🔓 Tích hợp Cheat Engine:** Hỗ trợ sẵn hệ thống cheat (bất tử, vô hạn xèng, unlock màn...) cho những tựa game quá "hardcore".

## 📥 Tải xuống & Cài đặt

Ứng dụng được biên dịch sẵn thành các file APK cho từng kiến trúc máy để tối ưu dung lượng tải.

1. Truy cập mục [Releases](../../releases) trên repository này.
2. Tải file `.apk` phù hợp với thiết bị của bạn.
3. **Lưu ý:** Vì đây là file APK tải ngoài cửa hàng, bạn cần bật tính năng **"Cài đặt ứng dụng từ nguồn không xác định" (Install apps from unknown sources)** trong cài đặt bảo mật của Android trước khi cài đặt.

## 📸 Ảnh chụp màn hình (Screenshots)

*(Thêm 1-2 ảnh giao diện vuông vắn và cảnh đang chơi game có bật cheat tại đây)*
<p align="center">
  <img src="link_anh_1.jpg" width="300" />
  <img src="link_anh_2.jpg" width="300" />
</p>

## 🛠️ Dành cho Developer

Dự án sử dụng các thư viện core ổn định nhất. Mọi luồng xử lý và handle tài nguyên đều được kiểm tra lỗi (error handling) cẩn thận trước khi output ra UI. 

Nếu bạn phát hiện bug, vui lòng mở issue kèm theo log và cấu hình thiết bị.

---
**Tác giả:** [tatadoan]

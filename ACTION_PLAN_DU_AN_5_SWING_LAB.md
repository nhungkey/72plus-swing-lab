# BẢNG HÀNH ĐỘNG MASTER (ACTION PLAN) — DỰ ÁN 5: 72+ SWING LAB
> **Thương hiệu:** 72+ Golf Academy | **Hệ thống:** Native OnForm Pro Clone 100% (Phase 1)  
> **Phương pháp quản trị:** **TOP-DOWN APPROACH** (Tập trung làm sâu & dứt điểm 100% Module 1 Studio 1-Clip trước khi sang các Module khác).

---

## 📋 BẢNG TIẾN ĐỘ THỰC THI TOP-DOWN DỨT ĐIỂM MODULE 1 (MH-01)

| Mã Bước | Tên Đầu Mục Công Việc | Người Phụ Trách | Trạng Thái minh Chứng | Link Đính Kèm Tài Liệu Minh Chứng |
| :--- | :--- | :--- | :--- | :--- |
| **B1.1-MH01** | Reverse Engineering & Feature Matrix Module 1 | `[An thực hiện]` | ✅ **Hoàn thành 100%** | [Hồ sơ BA Module 1](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/BA_REVERSE_ENGINEERING_MODULE_1_MH01.md) |
| **B2.1-MH01** | Design System & 7 UI Snapshots Module 1 | `[An thực hiện]` | ✅ **Hoàn thành 100%** | [Hồ sơ Design System Module 1](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/DESIGN_SYSTEM_MODULE_1_MH01.md) |
| **B3.1-MH01** | Architecture H.264 60FPS & 2D Canvas Engine | `[An thực hiện]` | ✅ **Hoàn thành 100%** | [Script Architecture Engine Step 3](file:///Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/scratch/verify_step3_architecture_engine_mh01.js) |
| **B4.1-MH01** | Coding Thao Tác Thật Module 1 (Camera, Up Video, Lines, Text, Tempo) | `[An thực hiện]` | ✅ **Hoàn thành 100%** | [Code HTML Master Module 1 index.html](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/index.html) |
| **B5.1-MH01** | QA Audit 1:1 Đối Chiếu Native OnForm Pro | `[An thực hiện]` | ✅ **Hoàn thành 100%** | [Script QA Audit Step 5 Pass 16/16](file:///Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/scratch/verify_step5_qa_audit_mh01.js) |
| **B6.1-MH01** | Nghiệm Thu & Khóa Mốc Module 1 Dứt Điểm | `[CEO Nhung Nguyễn xác nhận]` | 🟡 **ĐANG CHỜ CEO NGHIỆM THU** | *(Sẵn sàng chờ CEO nghiệm thu Module 1)* |

---

## 🖼️ HỒ SƠ ẢNH MINH HỌA TRỰC QUAN 5 MÀN HÌNH CHUẨN ONFORM PRO (BƯỚC 1.1)
> **Dành cho CEO Nhung Nguyễn rà soát & duyệt hình ảnh từng màn hình trước khi thiết kế mã nguồn**

### 1. Màn Hình MH-01: Studio Phân Tích Đơn 1 Clip (Full-Screen Video + Controls)
- **Mô tả:** Màn hình đen tràn viền 100%, không viền card. Thanh trên cùng chứa nút nạp clip, nút chuyển Dual/Overlay. Thanh đáy chứa nút tua chậm 0.25x, tua từng khung hình (Frame-by-frame), cụm chỉnh ISO/Shutter Speed.
![MH-01 Studio Phân Tích Đơn 1 Clip](/Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/onform_screen_1_single_1787738678662.jpg)

---

### 2. Màn Hình MH-02: Studio Phân Tích Kép & Đè Nét Mờ 60FPS (Side-by-Side & Overlay)
- **Mô tả:** Màn hình chia đôi 2 cột (Trái: Học viên / Phải: Clip Pro). Có nút `[⚡ Impact Sync]` tự động khóa mốc chạm bóng và Slider Opacity 0-100% đè nét mờ 2 hình ảnh.
![MH-02 Studio Phân Tích Kép & Đè Nét Mờ 60FPS](/Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/onform_screen_2_dual_1787738732226.jpg)

---

### 3. Màn Hình MH-03: Bộ Công Cụ Vẽ Kỹ Thuật (Floating Vertical Markup Toolbar)
- **Mô tả:** Thanh công cụ vẽ nổi dọc bên lề màn hình gồm: Đường thẳng Plane, Khung tròn Head Box, Thước đo góc ° tự động, Mũi tên chỉ hướng, Bộ đếm nhịp Tempo 3:1 và Palette 4 màu 72+.
![MH-03 Bộ Công Cụ Vẽ Kỹ Thuật](/Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/onform_screen_3_markup_1787738765372.jpg)

---

### 4. Màn Hình MH-04: Thu Âm Bài Giảng Voiceover (Lesson Video Recorder MP4)
- **Mô tả:** Nút Mic đỏ thu âm màn hình + micro HLV. Khi bấm kết thúc tự động đóng gói bài giảng video MP4 (tối đa 5 phút) để gửi Zalo cho học viên.
![MH-04 Thu Âm Bài Giảng Voiceover](/Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/onform_screen_4_voiceover_1787738831137.jpg)

---

### 5. Màn Hình MH-05: Thư Viện Folder Học Viên & Sổ Ghi Chú HLV (Student Library & Coach Notes)
- **Mô tả:** Quản lý folder theo tên Học viên, sắp xếp clip theo Mốc 1 (Buổi 6), Mốc 2 (Buổi 12)... kèm ô Note lưu vết bài giảng ca trước của HLV.
![MH-05 Thư Viện Folder Học Viên & Sổ Ghi Chú HLV](/Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/onform_screen_5_library_1787738883311.jpg)

---

### 6. Màn Hình MH-06: Trang Chủ & Tài Khoản Cá Nhân HLV (Coach Home & Account Profile)
- **Mô tả:** Bảng tổng quan thông tin HLV (Họ tên, Hạng HLV IGF/SGC/LGC/PRE, Cơ sở phân công), các thẻ chỉ số (Tổng học viên, Tổng clip), Nhật ký hoạt động gần nhất và Trạng thái đồng bộ lưu trữ iCloud Drive 72+.
![MH-06 Trang Chủ & Tài Khoản Cá Nhân HLV](/Users/nhungnguyen/.gemini/antigravity-ide/brain/c239bedb-539c-4b6c-ba2a-04f17b414019/onform_screen_6_home_account_1787740470325.jpg)

---

## 📄 TỔNG HỢP LINK TÀI LIỆU DỰ ÁN 5 (PROJECT RESOURCE LINKS)

1. [File Hướng Dẫn Dự Án Master `HUONG_DAN_DU_AN.md`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/HUONG_DAN_DU_AN.md)
2. [File Bảng Tiến Độ Action Plan Master `ACTION_PLAN_DU_AN_5_SWING_LAB.md`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/ACTION_PLAN_DU_AN_5_SWING_LAB.md)
3. [File Hồ Sơ BA Chuyên Sâu OnForm `BA_CHUYEN_SAU_ONFORM_PRO.md`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/BA_CHUYEN_SAU_ONFORM_PRO.md)
4. [File Hồ Sơ Phản Biện 4 Chuyên Gia `HO_SO_PHAN_BIEN_4_CHUYEN_GIA.md`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/HO_SO_PHAN_BIEN_4_CHUYEN_GIA.md)
5. [File Thiết Kế Design System `DESIGN_SYSTEM_ONFORM_PRO.md`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/DESIGN_SYSTEM_ONFORM_PRO.md)
6. [Hồ Sơ Trực Quan Đa Thiết Bị `gallery_responsive_devices.html`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/gallery_responsive_devices.html)
7. [Trang Mẫu Giao Diện Prototype 6 Màn Hình `app_onform_pro_native_master.html`](file:///Users/nhungnguyen/Library/Mobile%20Documents/com~apple~CloudDocs/72PLUS_WORKSPACE/01_GOLF_ACADEMY_GA/DU_AN_5_APP_72PLUS_SWING_LAB/app_onform_pro_native_master.html)

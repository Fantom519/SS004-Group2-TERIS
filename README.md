# 🎮 F5 - Tetris Game Project

![University](https://img.shields.io/badge/UIT-VNUHCM-00558d?style=for-the-badge)
![Course](https://img.shields.io/badge/Class-SS004.R11-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Progress%20(Week%201)-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-Academic-purple?style=for-the-badge)

Dự án xây dựng và phát triển tựa game xếp gạch kinh điển **Tetris** thuộc đồ án môn học lớp **SS004.R11** (Trường Đại học Công nghệ Thông tin - ĐHQG TP.HCM), thực hiện bởi **Nhóm F5**. 

> **📌 Trạng thái hiện tại (Tuần 1):** Repository đang lưu trữ **mã nguồn khởi tạo (Starter Code)** do giảng viên cung cấp. Nhóm đã hoàn tất thiết lập quy trình làm việc, phân công nhiệm vụ và phân tích yêu cầu hệ thống để sẵn sàng phát triển tính năng từ Tuần 2.

---

## 🛠️ Công cụ & Quy trình làm việc (Tools & Workflow)

Dự án tập trung vào sự tinh gọn, hiệu quả với các công cụ quản lý và lập trình quen thuộc:

### Môi trường lập trình & Quản lý mã nguồn
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Quản lý tiến độ, Giao tiếp & Báo cáo
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Overleaf](https://img.shields.io/badge/Overleaf-47A141?style=for-the-badge&logo=overleaf&logoColor=white)

* **Trao đổi công việc (Slack):** Channel `#24521320_24521343_24521363` *(Cam kết phản hồi trong vòng 24h)*.
* **Quản lý công việc (Trello):** `[Dán Link Trello Board của nhóm vào đây]`
* **Báo cáo học thuật (Overleaf):** `[Dán Link Project Overleaf của nhóm vào đây]`

---

## 📌 Tính năng cốt lõi (Core Features)

- [x] **Starter Code Setup:** Khởi tạo cấu trúc dự án cơ bản từ mã nguồn mẫu của giảng viên.
- [ ] **Hệ thống 7 khối gạch (Tetromino):** Tạo ngẫu nhiên và hiển thị 7 khối gạch chuẩn (`I, O, T, S, Z, J, L`) với màu sắc phân biệt.
- [ ] **Điều khiển linh hoạt:** Hỗ trợ di chuyển trái/phải (`←`/`→`), xoay khối (`↑`), rơi nhanh (`↓` - Soft Drop) và thả rơi tức thì (`Space` - Hard Drop).
- [ ] **Xóa hàng & Tính điểm:** Tự động nhận diện hàng ngang lấp đầy, xóa hàng và cộng điểm thưởng (đặc biệt tối ưu điểm khi đạt cú ăn 4 hàng *Tetris*).
- [ ] **Tăng cấp độ (Level Progression):** Tăng tốc độ rơi của khối gạch theo số hàng người chơi đã xóa được.
- [ ] **Tính năng hỗ trợ chiến thuật:** Xem trước khối kế tiếp (**Next**), giữ khối tạm thời (**Hold**) và hiển thị bóng mờ căn chỉnh (**Ghost Piece**).
- [ ] **Quản lý trạng thái ván chơi:** Tạm dừng/Tiếp tục (`P`), chơi lại ván mới và màn hình tổng kết điểm khi **Game Over**.

---

## 🏗️ Cấu trúc thư mục (Project Structure)

Cấu trúc dự án được tổ chức đơn giản, dễ đọc và thuận tiện cho việc chia nhánh (branch) làm việc nhóm:

```text
F5-Tetris-Project/
├── assets/                 # Chứa tài nguyên hình ảnh, âm thanh, font chữ của game
├── docs/                   # Tài liệu báo cáo tuần, biên bản họp và tài liệu thiết kế
├── src/                    # Mã nguồn chính của trò chơi (Starter code & các module phát triển)
├── .gitignore              # Các file tạm/cấu hình cá nhân không đẩy lên Git
└── README.md               # Tài liệu giới thiệu và hướng dẫn dự án

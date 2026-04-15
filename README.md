# 💻 Windows 95 Emulation for Android (Samsung Galaxy Edition)

Dự án mô phỏng giao diện và trải nghiệm hệ điều hành Windows 95 trên nền tảng Web. Toàn bộ mã nguồn được tối ưu hóa để chạy mượt mà trên trình duyệt di động, đặc biệt là các dòng máy Samsung Galaxy.

![Windows 95 Badge](https://img.shields.io/badge/OS-Windows_95-blue?style=for-the-badge&logo=windows)
![Platform](https://img.shields.io/badge/Platform-Mobile_Web-green?style=for-the-badge)
![Privacy](https://img.shields.io/badge/Privacy-Protected-success?style=for-the-badge)

## 🚀 Tính năng cốt lõi

Dự án tái hiện hệ thống Windows cổ điển với khả năng tương tác sâu vào thông số thiết bị thực tế của người dùng thông qua trình duyệt:

* **Real-time Task Manager**: Sử dụng `Performance API` để kiểm tra dung lượng RAM và tiến trình thực tế trình duyệt đang chiếm dụng.
* **Hardware Detection**: Tự động nhận diện số nhân CPU (Cores), loại thiết bị và độ phân giải màn hình qua các hàm API hệ thống.
* **Advanced Clock**: Đồng hồ hỗ trợ giao diện Analog và Digital, tích hợp khả năng đồng bộ thời gian thực từ thiết bị.
* **Win95 Design System**: Giao diện sử dụng bảng màu chuẩn `#008080` và hiệu ứng đổ bóng đặc trưng của năm 1995.

## 📁 Danh sách 8 ứng dụng tích hợp

Dự án bao gồm 8 công cụ hệ thống và giải trí cơ bản:

| STT | Ứng dụng | Tên file | Chức năng chính |
| :--- | :--- | :--- | :--- |
| 1 | **Task Manager** | `task.html` | Kiểm tra RAM, CPU và quản lý tác vụ hệ thống |
| 2 | **Control Panel** | `panel.html` | Xem chi tiết thông số phần cứng thiết bị |
| 3 | **MS Paint** | `paint.html` | Công cụ vẽ đồ họa cổ điển |
| 4 | **Notepad** | `notepad.html` | Trình soạn thảo văn bản, hỗ trợ lưu file .txt |
| 5 | **Media Player** | `wmp.html` | Trình phát nhạc và video đa phương tiện |
| 6 | **Winver** | `winver.html` | Hiển thị phiên bản hệ thống và trạng thái phần cứng |
| 7 | **Clock Pro** | `clock_pro_95.html` | Đồng hồ đa năng hỗ trợ tùy chỉnh thủ công |
| 8 | **Minesweeper** | `minesweeper_95.html` | Trò chơi Dò mìn phiên bản chuẩn |

## 🛠️ Công nghệ sử dụng

* **Ngôn ngữ**: HTML5, CSS3, JavaScript (ES6+).
* **System APIs**: `Performance.memory`, `navigator.deviceMemory`, `hardwareConcurrency`.
* **Tương thích**: Google Chrome Android, Samsung Internet.

---
*Lưu ý: Dự án được phát triển cho mục đích nghiên cứu và học tập cá nhân. Mọi quyền lợi về thương hiệu Windows 95 thuộc về Microsoft. Mã nguồn không chứa bất kỳ trình theo dõi dữ liệu cá nhân nào.*

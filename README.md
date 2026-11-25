# 🎯 PUBG Recoil Assistant (Công cụ Hỗ trợ Ghìm Tâm)

Một tiện ích chạy trên nền tảng desktop giúp hỗ trợ kiểm soát độ giật (vertical recoil) của vũ khí thông qua việc mô phỏng chuyển động chuột tự động theo cấu hình định sẵn.

> ⚠️ **Tuyên bố miễn trừ trách nhiệm (Disclaimer):** 
> Dự án này được xây dựng **chỉ nhằm mục đích học tập, nghiên cứu** về xử lý sự kiện bàn phím/chuột (Input Hooks) và tự động hóa giao diện trên Windows. Việc sử dụng các công cụ bên thứ ba trong môi trường trò chơi trực tuyến có thể vi phạm Điều khoản dịch vụ (ToS) của nhà phát hành và dẫn đến khóa tài khoản. Tác giả không chịu trách nhiệm cho bất kỳ hậu quả nào phát sinh từ việc sử dụng phần mềm này.

---

## ✨ Tính năng chính

* **Hồ sơ vũ khí tùy chỉnh (Weapon Profiles):** Dễ dàng thiết lập và lưu thông số độ giật riêng biệt cho từng loại súng (M416, AKM, Beryl M762, v.v.) và phụ kiện đi kèm.
* **Chuyển đổi nhanh bằng phím tắt (Hotkeys):** Bật/tắt chế độ hỗ trợ hoặc chuyển đổi nhanh giữa vũ khí chính/phụ ngay trong lúc thao tác.
* **Điều chỉnh độ nhạy linh hoạt:** Tùy chỉnh tốc độ kéo chuột (Y-axis) và độ trễ (Delay) theo từng miligiây để phù hợp với DPI chuột và độ nhạy trong game.
* **Giao diện trực quan (GUI):** Bảng điều khiển gọn nhẹ, hiển thị trạng thái hoạt động theo thời gian thực.

---

## 🛠️ Công nghệ sử dụng

* **Ngôn ngữ:** Python 3.x *(hoặc C# / .NET - cập nhật theo ngôn ngữ bạn dùng)*
* **Thư viện giao diện:** `Tkinter` / `CustomTkinter` *(hoặc WinForms/WPF)*
* **Xử lý Input:** `pynput`, `ctypes` (Windows API `SendInput` / `mouse_event`)
* **Lưu trữ cấu hình:** `JSON`

---

## 🚀 Cài đặt và Sử dụng

### 1. Yêu cầu hệ thống
* Hệ điều hành: Windows 10 / Windows 11
* Python 3.8 trở lên (nếu chạy từ mã nguồn)

### 2. Cài đặt từ mã nguồn
Clone repository về máy và cài đặt các thư viện cần thiết:

```bash
git clone [https://github.com/username/pubg-recoil-assistant.git](https://github.com/username/pubg-recoil-assistant.git)
cd pubg-recoil-assistant
pip install -r requirements.txt
cẩn thận có viruss thằng ngu

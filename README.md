# UDP Client-Server (C# Windows Forms)

Đây là một ứng dụng **UDP Client-Server** được viết bằng **C# Windows Forms**, cho phép truyền tin nhắn giữa client và server thông qua giao thức UDP.

## 🚀 Tính năng
### ✅ **Server**
- Nhập cổng và lắng nghe các tin nhắn gửi đến.
- Hiển thị nội dung tin nhắn từ client.
- Cho phép dừng và khởi động lại server.
- Đóng kết nối an toàn khi thoát ứng dụng.

### ✅ **Client**
- Nhập địa chỉ IP, cổng và tin nhắn để gửi đến server.
- Gửi dữ liệu bằng giao thức UDP.
- Xóa nội dung nhập liệu.
- Đóng kết nối an toàn khi thoát ứng dụng.

---

## 📂 Cấu trúc thư mục
```
/UDP_Client_Server
│── /UDP_Client
│   ├── Client.cs
│   ├── Client.Designer.cs
│   ├── Program.cs
│   ├── App.config
│   ├── UDP_Client.csproj
│   ├── UDP_Client.sln
│── /UDP_Server
│   ├── Server.cs
│   ├── Server.Designer.cs
│   ├── Program.cs
│   ├── App.config
│   ├── UDP_Server.csproj
│   ├── UDP_Server.sln
│── README.md
```

---

## ⚡ Hướng dẫn sử dụng

### 🔹 **Chạy Server**
1. Chạy ứng dụng `UDP_Server`.
2. Nhập số **Port** (ví dụ: `8888`).
3. Nhấn **Listen** để bắt đầu lắng nghe.

### 🔹 **Chạy Client**
1. Chạy ứng dụng `UDP_Client`.
2. Nhập **IP Address** (ví dụ: `127.0.0.1` nếu chạy local) và **Port** (trùng với server).
3. Nhập tin nhắn và nhấn **Send** để gửi.

---

## 🛠 Công nghệ sử dụng
- **C# Windows Forms**
- **UDP (User Datagram Protocol)**
- **.NET Framework**

---

## 📌 Ghi chú
- Nếu chạy trên mạng LAN, hãy đảm bảo **firewall không chặn port UDP**.
- Nếu cần chạy qua Internet, cần thiết lập **port forwarding** trên router.

---

📌 **Tác giả**: [Vh.Koiiin](https://github.com/Koiiin)



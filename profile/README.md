# Ping Me: Multi Service Social Network

PingMe là **nền tảng mạng xã hội đa năng**, được xây dựng theo kiến trúc **client–server hiện đại**, cho phép người dùng giao tiếp, chia sẻ nội dung, giải trí và quản lý tiện ích cá nhân trong **một hệ sinh thái thống nhất**.

Mục tiêu của PingMe là cung cấp trải nghiệm **liền mạch, realtime, an toàn và dễ mở rộng**, phục vụ cả web và mobile.

---

## 🌐 Tổng quan hệ sinh thái

```txt
PingMe Platform
 ├─ Frontend Web (ReactJS)
 ├─ Mobile App (React Native)
 ├─ Backend Services (REST + Websocket/STOMP)
 ├─ Database SQL & NoSQL & Cache
 └─ Admin & Monitoring
```

---

## 🚀 Chức năng cốt lõi

### 🔐 Xác thực & Bảo mật

- Đăng ký / Đăng nhập / Đăng xuất
- JWT (Access / Refresh Token)
- Quên mật khẩu (OTP qua Email)
- Quản lý phiên đăng nhập đa thiết bị
- Phân quyền User / Admin

### 💬 Giao tiếp Realtime

- Chat 1–1 và chat nhóm
- WebSocket / STOMP
- Tin nhắn văn bản, emoji, hình ảnh, video, file
- Thông báo realtime
- Gọi video trực tiếp (WebRTC)

### 👥 Kết nối xã hội

- Tìm kiếm người dùng
- Kết bạn, quản lý danh sách bạn bè
- Hồ sơ cá nhân & avatar

### 📝 Nội dung & Giải trí

- Blog: đăng bài, bình luận, quản lý nội dung
- Reels: video ngắn, feed đề xuất, tương tác
- Music: nghe nhạc, album, nghệ sĩ, thể loại
- Weather: cập nhật thời tiết

---

## 🏗️ Kiến trúc tổng thể

```txt
Client (Web / Mobile)
 ├─ SPA / Native App
 ├─ API Layer
 └─ Realtime Channel

Backend
 ├─ RESTful Services
 ├─ WebSocket / STOMP
 ├─ Authentication & Authorization
 ├─ Business Logic
 └─ Admin Services

Infrastructure
 ├─ Database (RDBMS)
 ├─ Cache / Session Store
 └─ Deployment & CI/CD
```

---

## 🧰 Công nghệ sử dụng (tổng quát)

### Frontend

- React (Web)
- React Native / Expo (Mobile)
- TypeScript
- State Management (Redux Toolkit)
- WebSocket Client

### Backend

- Spring Boot
- REST API
- WebSocket / STOMP
- JWT Security
- Redis (cache, session, OTP)

### Database & Infra

- MariaDB / MySQL
- Redis
- Cloud / VPS
- CI/CD

---

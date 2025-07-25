# Booking API System

Sistem ini adalah backend RESTful API berbasis Node.js dan Express.js yang digunakan untuk mengelola proses otentikasi, booking layanan, manajemen role, user, dan paket layanan. API ini menggunakan middleware JWT untuk autentikasi dan proteksi endpoint.

## 🔧 Tech Stack

- Node.js
- Express.js
- JWT (JSON Web Token) untuk autentikasi
- Middleware otentikasi


## 📌 Endpoint List

### 🔐 Auth

| Method | Endpoint        | Description      |
|--------|------------------|------------------|
| POST   | `/login`         | Login user       |
| POST   | `/register`      | Register user    |

---

### 👥 Role

| Method | Endpoint       | Description         |
|--------|----------------|---------------------|
| GET    | `/role/`       | Get all roles       |
| POST   | `/role/`       | Create new role     |
| PUT    | `/role/:id`    | Update role by ID   |
| DELETE | `/role/:id`    | Delete role by ID   |

🔒 Dilindungi oleh autentikasi JWT

---

### 📦 Package

| Method | Endpoint         | Description            |
|--------|------------------|------------------------|
| GET    | `/package/`      | Get all packages       |
| POST   | `/package/`      | Create new package     |
| PUT    | `/package/:id`   | Update package by ID   |
| DELETE | `/package/:id`   | Delete package by ID   |

🔒 Dilindungi oleh autentikasi JWT

---

### 📅 Booking

| Method | Endpoint           | Description                |
|--------|--------------------|----------------------------|
| GET    | `/booking/`        | Get all bookings           |
| GET    | `/booking/time`    | Get available booking time |
| GET    | `/booking/:id`     | Get booking by ID          |
| POST   | `/booking/`        | Create new booking         |
| PUT    | `/booking/:id`     | Update booking status      |
| DELETE | `/booking/:id`     | Delete booking by ID       |

🔒 Dilindungi oleh autentikasi JWT

---

### 👤 User

| Method | Endpoint       | Description         |
|--------|----------------|---------------------|
| GET    | `/user/`       | Get all users       |
| PUT    | `/user/:id`    | Update user by ID   |
| DELETE | `/user/:id`    | Delete user by ID   |

🔒 Dilindungi oleh autentikasi JWT

---

## ▶️ Cara Menjalankan

1. Clone repo:
   ```bash
   git clone https://github.com/Dionisius951/carwash_api
   cd repo-name
2. Install Dependency:
   ```bash
   npm install
3. Jalankan Server:
   ```bash
   npm run dev



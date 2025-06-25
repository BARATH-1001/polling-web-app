# 🗳️ Online Voting System

An end-to-end full-stack web application that enables secure, real-time online voting. Built with modern development practices, it separates frontend and backend concerns, and ensures secure authentication, clean structure, and configurable environment variables via `.env`.

---

## 🚀 Features

### 👨‍💻 Client (Frontend)
- Responsive voting UI (HTML/CSS/JS or React)
- Login & authentication interface
- Vote casting dashboard
- Real-time status updates
- Error & alert handling on screen

### 🖥️ Server (Backend)
- REST API using Node.js & Express.js
- MongoDB with Mongoose for DB management
- User management: register/login
- JWT-based secure authentication
- Modular structure (routes/controllers/models)

### 🔐 Environment Setup (`.env`)
- Keeps sensitive info private
- Configure easily in `server/.env`

Example `.env`:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

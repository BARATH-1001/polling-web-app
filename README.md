# 🗳️ Online Voting System

A secure and efficient web-based voting system built with a full-stack architecture. It supports voter authentication, real-time vote casting, and result viewing. The project is structured into separate **client** and **server** folders, and follows industry practices like JWT authentication, bcrypt hashing, and environment variable protection.

---

## 🌟 Features

### 🧑‍💻 Client (Frontend)
- Responsive and interactive voting interface
- User login and authentication
- Real-time voting feedback
- Result visualization (optional)
- Developed using HTML, CSS, JavaScript (or React)

### 🖥️ Server (Backend)
- RESTful API built with Node.js and Express.js
- MongoDB for user and vote data storage
- Secure endpoints with JWT authentication
- Password hashing with Bcrypt
- Modular folder structure for controllers, routes, models

### 🔐 Environment (.env) Configuration
- `.env` file stores sensitive configurations:
  - `PORT`: Port on which backend runs
  - `MONGO_URI`: MongoDB connection URI
  - `JWT_SECRET`: Secret key for JSON Web Tokens

---

## 📁 Folder Structure


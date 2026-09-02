# ChatRealtime

ChatRealtime is a real-time 1-to-1 messaging application that allows users to communicate with each other through text messages, images, and voice calls.

## 📌 About The Project

ChatRealtime is a personal project built to practice and apply knowledge of:

- Frontend development
- Backend development
- RESTful API
- Real-time communication
- WebSocket / Socket.IO
- Database design
- Authentication & Authorization
- File upload
- WebRTC
- Software architecture

The project focuses on a simple and lightweight messaging experience similar to basic messaging applications.

## ✨ Features

### 🔐 Authentication

- Register account
- Login
- Logout
- Authentication
- Password hashing
- Protected APIs

### 👤 User

- View personal profile
- Update profile
- Update avatar
- Search users
- View online/offline status
- View last seen

### 💬 1-to-1 Chat

- Create conversation
- Send text messages
- Receive messages in real-time
- View message history
- Message timestamps
- Read/unread status

### 🖼️ Image Messaging

- Send images
- Preview images before sending
- Display images inside conversation
- Store image information

### 📞 Voice Call

- 1-to-1 voice call
- Incoming call
- Accept call
- Reject call
- End call
- Call status
- Call history

> Video calls are not included in this project.

## 🛠️ Technologies

### Frontend

- React
- Vite
- JavaScript
- HTML
- CSS
- Axios
- Socket.IO Client

### Backend

- Node.js
- Express.js
- Socket.IO
- REST API

### Database

- PostgreSQL

### Real-time Communication

- Socket.IO
- WebSocket

### Voice Call

- WebRTC

### Development Tools

- Git
- GitHub
- VS Code

## 📁 Project Structure

```text
chatrealtime/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── context/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── sockets/
│   │   ├── config/
│   │   └── app.js
│   │
│   ├── package.json
│   └── .env
│
├── .gitignore
└── README.md

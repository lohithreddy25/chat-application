# 💬 MERN Stack Chat Application

This is a real-time chat application built with the **MERN (MongoDB, Express.js, React, Node.js)** stack. It features secure user authentication, real-time messaging using **Socket.IO**, and a modern, responsive frontend interface.

---

## 🏗️ Tech Stack

### Backend:
- **Node.js** with **Express.js**
- **MongoDB** for data persistence
- **Mongoose** for object modeling
- **JWT-based authentication**
- **BCrypt** for password hashing
- **Socket.IO** for real-time communication

### Frontend:
- **React.js**
- **Tailwind CSS** for styling
- **React Router** for page navigation
- **Axios** for API requests
- **React Context API** for state management
- **React Hot Toast** for user notifications

---

## 🚀 Features

### 👤 User Functionality:
- Secure signup & login using JWT
- Real-time one-to-one messaging
- User search and chat initiation
- Display of online/offline status
- Chat list with latest message preview
- Message timestamps and read indicators
- Toast-based notifications for new messages

### 🧰 Developer Features:
- Clean API architecture using Express Router
- Efficient message & user schema modeling with Mongoose
- Modular backend with reusable middleware (auth, error handling)
- Scalable Socket.IO integration for multiple users

---

## 🌐 API Endpoints

| Module       | Endpoint                      | Access Level   |
|--------------|-------------------------------|----------------|
| Auth         | `/api/auth/login`, `/register`| Public         |
| Users        | `/api/users/`, `/search`      | Authenticated  |
| Chats        | `/api/chats/`, `/create`      | Authenticated  |
| Messages     | `/api/messages/`, `/send`     | Authenticated  |



## ⚙️ Local Setup

### 🖥️ Requirements:
- Node.js v16+
- MongoDB (local or Atlas)
- npm or yarn

### 🛠️ Steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/mern-chat-app.git

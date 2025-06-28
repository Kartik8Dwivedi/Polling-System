# Real-Time Polling App

A full-stack real-time polling system that enables teachers to create and manage live polls, while students can participate and vote in real time. Built using **Node.js**, **Express.js**, **MongoDB**, **React (Vite)**, and **Socket.IO**.

---

## 🔧 Tech Stack

### Backend
- **Node.js** (v22.5.1)
- **Express.js**
- **MongoDB** (for data persistence)
- **Socket.IO** (for real-time communication)

### Frontend
- **React** (with Vite)
- **Socket.IO-client**
- **Bootstrap** (for UI styling)
- **Session Storage** (for managing user sessions)

---

## ⚙️ Features

### 🧑‍🏫 Teacher
- Create live polls with multiple options.
- Set timers for polls.
- View real-time voting results.
- Kick students from poll rooms.
- View history of previously created polls.

### 🧑‍🎓 Student
- Join poll rooms via room codes.
- Vote in real time.
- Get redirected if kicked from the room.

---

## 📆 Repository Structure

```bash
backend/   # Backend service (Node.js, Express, MongoDB, Socket.IO)
frontend/  # Frontend client (React, Vite, Socket.IO-client, Bootstrap)
```

---

## 🚀 Getting Started

### Backend Setup

#### Prerequisites
- Node.js (v22.5.1 or later)
- npm
- MongoDB

#### Installation
```bash
git clone <repository-url>
cd my-app/backend
npm install
npm start
```

#### Server will be available at:
```bash
http://localhost:3000
```

---

### Frontend Setup

#### Prerequisites
- Node.js (v22.5.1 or later)
- npm

#### Installation
```bash
git clone <repository-url>
cd my-app/frontend
npm install
npm run dev
```

#### App will run at:
```bash
http://localhost:5173
```

---

## 📡 Communication
Real-time features are handled via **Socket.IO** for both teacher and student workflows.

---

## 📂 Environment Variables
Ensure environment variables (like MongoDB URI, server port, etc.) are configured properly in the `.env` file in the backend project.

---

## 📜 License
This project is licensed under the MIT License.

---

## 🙌 Contributions
Pull requests and issues are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 👨‍💼 Author
**Saran Mani**

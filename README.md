# 🧠 Task Manager (MERN Stack)

A full-stack **Task Management Dashboard** built using **React**, **Node.js**, **Express**, and **MongoDB Atlas**.

This project allows users to create, update, delete, and filter tasks with features like deadline alerts, search, toast notifications, and a responsive layout.

---

## 🚀 Features

- 🔐 JWT-based User Registration & Login
- ✅ Add / Edit / Delete Tasks
- 🕓 Deadline Alerts (⏰ Overdue, ⚠️ Due Today)
- 🧾 Filter by Task Status (Pending, In Progress, Completed)
- 🔎 Search Tasks by Title
- 🌗 Dark Mode Toggle
- 🔄 Visual Loading Spinner
- 📱 Responsive UI (Mobile Friendly)
- 🚫 Toast Alerts for Errors & Success (react-hot-toast)

---

## 🛠 Tech Stack

| Frontend          | Backend           | Database      |
| ----------------- | ----------------- | ------------- |
| React (Bootstrap) | Node.js + Express | MongoDB Atlas |

---

## 📦 Project Structure

task-manager/
├── backend/ # Node.js Express API
│ ├── routes/
│ ├── models/
│ ├── middleware/
│ └── server.js
├── frontend/ # React frontend
│ ├── src/
│ │ ├── pages/
│ │ └── components/
├── .env # Environment variables (not pushed)
├── README.md
└── .gitignore

## ⚙️ Setup Instructions

### 🖥 Backend

```bash
cd backend
npm install
cp .env.example .env     # Add your MongoDB URI & JWT_SECRET
nodemon server.js

🌐 Frontend

cd frontend
npm install
npm start
```

POST /api/auth/register
{
"name": "Test User",
"email": "test@example.com",
"password": "123456"
}

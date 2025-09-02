# Task-Manager-MERN-Stack-React-Node.js-Express-MongoDB-
A full-stack task management web application built with the MERN stack. Features include user authentication (JWT), task CRUD operations, and a responsive React frontend.
# Task Manager – MERN Stack

A full-stack **Task Management Web Application** built with the **MERN stack**  
(React, Node.js, Express, MongoDB).  

Users can register, log in, and manage their daily tasks with full **CRUD functionality**.  
This project demonstrates **authentication, REST APIs, frontend state management, and responsive UI**.

---

## 🚀 Features
- 🔐 **User Authentication** with JWT (register/login/logout)
- 📝 **CRUD operations** for tasks (create, update, delete)
- 🎨 **Responsive UI** built with React + Vite
- ⚡ RESTful API using Node.js + Express
- 🗄️ MongoDB for persistent storage

---

## 📂 Project Structure
task-manager/
│── client/ # React frontend
│ ├── src/ # Components & pages
│ └── .env.example
│
│── server/ # Express backend
│ ├── models/ # MongoDB models
│ ├── routes/ # API endpoints
│ └── .env.example
│
│── README.md
│── .gitignore

yaml
Copy code

---

## 🛠️ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/task-manager.git
cd task-manager
2. Backend Setup (server)
bash
Copy code
cd server
cp .env.example .env
npm install
npm run dev
Update .env with your MongoDB URI and JWT_SECRET.

3. Frontend Setup (client)
bash
Copy code
cd ../client
cp .env.example .env
npm install
npm run dev
Now open 👉 http://localhost:5173

📌 Requirements
Node.js (>= 18.x)

MongoDB (local or Atlas cloud)

npm or yarn


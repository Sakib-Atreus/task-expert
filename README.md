# Task Expert – Full Stack Task Management Application

## About
Task Expert is a **minimalistic, full-stack task management web application** built with **Next.js** on the frontend and **Express.js + MongoDB** on the backend. It helps users manage daily tasks efficiently using a clean UI, drag-and-drop workflow, analytics, and secure authentication.

The application supports three task stages — **Todo, Ongoing, and Completed** — with real-time UI and database updates.

## 🌐 Live Demo
**Frontend & Backend (Production):**  
https://taskexpert.vercel.app

## 📦 Source Code
- **Client-side:** https://github.com/Sakib-Atreus/task-expert/tree/main/task-expert-client 
- **Server-side:** https://github.com/Sakib-Atreus/task-expert/tree/main/task-expert-server

---

## 🛠 Tech Stack

### Frontend
- Next.js
- Redux Toolkit
- Tailwind CSS
- D3.js (Analytics & visualization)
- Firebase Authentication
- Axios
- React Toastify
- React Icons & Iconify

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)

---

## ✨ Key Features

### Client-side Features
- User authentication with **Firebase** (Register, Login, Delete Account)
- Secure dashboard for managing personal tasks
- Create, edit, delete tasks
- Pin up to **6 important tasks**
- Drag & drop tasks between **Todo, Ongoing, Completed** stages (HTML Drag & Drop API)
- Live countdown timer for task deadlines
- Task filtering, sorting (priority-based), and searching
- Analytics page showing an overview of user activity
- Profile management (username, password, profile photo)
- Fully responsive UI for all screen sizes

> ⚠️ *Note:* Touchscreen drag-and-drop support is currently under development and will be added soon.

---

### Server-side Features
- RESTful API architecture
- Secure authentication & authorization using **JWT**
- Token-based access control (users cannot access others' data)
- Automatic logout on token expiration
- MVC-based folder structure
- Strict schema-based data modeling using **Mongoose**
- Seamless synchronization between UI actions and database updates

---

## 🏗 Architecture Overview
- **Frontend:** Next.js + Redux Toolkit for UI and state management
- **Backend:** Express.js REST API following MVC pattern
- **Database:** MongoDB with Mongoose schemas
- **Authentication:** Firebase (frontend) + JWT (backend)

---

## 🚀 Future Improvements
- Touchscreen drag-and-drop support
- Performance optimization for large task lists
- Enhanced analytics and reports

---

## 📌 Summary
Task Expert is a complete **production-ready full-stack task management system** designed with scalability, security, and user experience in mind. It demonstrates clean architecture, modern frontend practices, and secure backend implementation.

---

**Developed by:** Sakib


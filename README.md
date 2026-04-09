# 📝 Task Manager Application

A simple and efficient full-stack Task Manager application that allows users to create, manage, and track their daily tasks.

This project was built as part of a technical assignment to demonstrate practical understanding of frontend and backend integration.

---

## 🚀 Features

* ➕ Add new tasks
* 📋 View all tasks
* ✅ Mark tasks as completed
* 🗑️ Delete tasks
* ⚡ Real-time UI updates with smooth interaction

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* JavaScript (ES6)
* Basic CSS

### Backend

* Node.js
* Express.js

### Storage

* In-memory data storage (as per assignment scope)

---

## 📂 Project Structure

```
task-manager-pooja/
│
├── backend/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── TaskForm.jsx
│   │   │   ├── TaskList.jsx
│   │   │   └── TaskItem.jsx
│   │   ├── App.jsx
│   │   └── api.js
│   └── package.json
│
└── README.md
```

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

git clone https://github.com/poojabahadhur/task-manager-pooja.git

cd task-manager-pooja

---

### 2️⃣ Run Backend

cd backend
npm install
node server.js

Server runs on: http://localhost:5001

---

### 3️⃣ Run Frontend

Open a new terminal:

cd frontend
npm install
npm run dev

App runs on: http://localhost:5173 (or any available port)

---

## 🔗 API Endpoints

| Method | Endpoint   | Description            |
| ------ | ---------- | ---------------------- |
| GET    | /tasks     | Fetch all tasks        |
| POST   | /tasks     | Create a new task      |
| PATCH  | /tasks/:id | Toggle task completion |
| DELETE | /tasks/:id | Delete a task          |

---

## 🎯 Key Highlights

* Clean separation of frontend and backend
* RESTful API design
* Functional React components with hooks
* Simple and intuitive UI
* Error handling for API calls

---

## 📌 Notes

* This project uses in-memory storage, so data resets when the server restarts.
* Designed to meet the assignment scope within the given time frame.

---

## 👩‍💻 Author

**Bahadhur Sri Pooja**
B.Tech CSE (AI & ML)
CMR College of Engineering and Technology

📧 [sripoojabahadhur06@gmail.com](mailto:sripoojabahadhur06@gmail.com)
🔗 https://www.linkedin.com/in/sri-pooja-bahadhur-159b74336

---

## 🙌 Acknowledgement

This project was developed as part of a technical internship assignment to demonstrate full-stack development skills.

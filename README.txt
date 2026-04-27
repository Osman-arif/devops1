# 🚀 Task Manager API

A RESTful API for managing daily tasks with authentication, built using Node.js and Express.

---

## 📖 Overview

This project allows users to create, update, delete, and manage tasks efficiently. It includes user authentication and secure data handling.

---

## ✨ Features

* 🔐 User Authentication (JWT)
* 📋 Create, Read, Update, Delete Tasks (CRUD)
* ⚡ Fast and scalable API
* 🛡️ Secure password hashing
* 🌐 RESTful architecture

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Auth:** JSON Web Tokens (JWT)
* **Tools:** Postman, Git

---

## 📂 Folder Structure

```id="u9z3cs"
task-manager-api/
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
└── server.js
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```id="n2kmql"
git clone https://github.com/your-username/task-manager-api.git
```

### 2. Navigate to project folder

```id="3fhw9d"
cd task-manager-api
```

### 3. Install dependencies

```id="fw6j97"
npm install
```

### 4. Setup environment variables

Create a `.env` file:

```id="5x9c6u"
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

### 5. Run the server

```id="2hgtu1"
npm run dev
```

---

## 📡 API Endpoints

| Method | Endpoint       | Description       |
| ------ | -------------- | ----------------- |
| POST   | /api/register  | Register new user |
| POST   | /api/login     | Login user        |
| GET    | /api/tasks     | Get all tasks     |
| POST   | /api/tasks     | Create new task   |
| PUT    | /api/tasks/:id | Update task       |
| DELETE | /api/tasks/:id | Delete task       |

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Usman Arif
GitHub: https://github.com/your-username

---

## ⭐ Show your support

Give a ⭐ if you like this project!

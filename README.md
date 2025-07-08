
# 🛡️ MERN Modular Auth App

A full-stack authentication system built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)** with **JWT-based auth**, **Bootstrap 5 UI**, and clean, reusable, modular code — ready to be extended into future projects.
---

## 🚀 Features

- 🔐 JWT Authentication (login/signup/logout)
- ✅ Protected Routes
- 🎨 Bootstrap 5 Styling
- ♻️ Reusable Auth Form Component
- 🌗 Dark/Light Mode Toggle
- 📦 Modular folder-based backend structure

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/rafainamdar04/authProj.git
cd authProj
````

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

> Create a `.env` file inside the `backend/` directory:

```
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/authApp
JWT_SECRET=your_jwt_secret_key
```

Start MongoDB if not already running:

```bash
mongod
```

Start the backend server:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

The React app should now be running at `http://localhost:3000`.

---

## 🔁 Reusability & Modularity

This project is designed to act as a **plug-and-play** base for any MERN app requiring authentication. You can reuse:

* `AuthContext` for handling user sessions
* `ProtectedRoute` wrapper to guard private routes
* `AuthForm` for both login and signup with show/hide password
* Clean Express structure (controllers, routes, middleware)

---

## 🧾 .gitignore

Add this file at the project root:

```
node_modules/
.env
.DS_Store
```


---

## ✅ Scripts

### Backend

| Command       | Description              |
| ------------- | ------------------------ |
| `npm run dev` | Runs server with nodemon |

### Frontend

| Command     | Description    |
| ----------- | -------------- |
| `npm start` | Runs React app |

---

## ⚙️ Requirements

* Node.js (>=18)
* MongoDB installed and running locally
* npm

---

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/fd07d9d7-607d-4677-baa6-f9127dc22373)
![image](https://github.com/user-attachments/assets/edf4b11c-f5d7-49a4-a973-cab419917176)
![image](https://github.com/user-attachments/assets/0069c083-2ec3-41ae-9e2c-75ac552a6807)

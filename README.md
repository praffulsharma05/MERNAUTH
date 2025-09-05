MERN Authentication
URL: https://lucent-yeot-a29382.netlify.app/


A complete **Authentication System** built with the **MERN stack** (MongoDB, Express, React, Node.js).
Includes user registration, login, JWT authentication, and protected routes.

---

## 🚀 Features

* 🔑 **User Registration & Login**
* 🛡️ **Password Hashing** with **bcryptjs**
* 📜 **JWT (JSON Web Token)** Authentication
* 🔒 **Protected Routes** (Frontend + Backend)
* ⚡ **RESTful APIs** with Express & MongoDB
* 🎨 **Modern UI** with React + Tailwind CSS (if used)
* 🌍 **CORS Enabled** for frontend-backend communication

---

##  Tech Stack

**Frontend:**

* React
* React Router
* Axios / Fetch API

**Backend:**

* Node.js
* Express.js
* MongoDB (Mongoose ODM)

**Authentication & Security:**

* bcryptjs
* jsonwebtoken
* dotenv

---

## 📂 Project Structure

```bash
mern-auth/
│
├── backend/         # Node.js + Express server
│   ├── config/      # DB connection & JWT config
│   ├── middleware/  # Auth middleware
│   ├── models/      # Mongoose models (User)
│   ├── routes/      # API routes (auth, users)
│   ├── server.js    # Main server file
│
├── frontend/        # React app
│   ├── src/
│   │   ├── components/  # UI Components
│   │   ├── pages/       # Login, Register, Dashboard
│   │   ├── App.js
│   │   ├── index.js
│
├── .env             # Environment variables
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone 
cd mern-auth
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/` and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

Run the backend:

```bash
npm run server
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🔑 API Endpoints

| Method | Endpoint             | Description            |
| ------ | -------------------- | ---------------------- |
| POST   | `/api/auth/register` | Register a new user    |
| POST   | `/api/auth/login`    | Login user & get token |
| GET    | `/api/auth/is-auth`  | Verify JWT & get user  |

---

## 📸 Screenshots
<img width="1907" height="898" alt="Screenshot 2025-09-05 170111" src="https://github.com/user-attachments/assets/7e4af872-1b98-4a52-9271-ef9fd3840e03" />

<img width="1909" height="916" alt="Screenshot 2025-09-05 170139" src="https://github.com/user-attachments/assets/fb02e3b8-9041-444d-841c-1db4a96642af" />

<img width="1899" height="899" alt="Screenshot 2025-09-05 170155" src="https://github.com/user-attachments/assets/71253054-6d94-4204-894e-f0847ee58ae0" />

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repo
2. Create a new branch (`feature/your-feature`)
3. Commit changes
4. Push and create a Pull Request

# TaskFlow — Task Management Web App

TaskFlow is a full-stack task management web application built with the **MERN stack**. It allows users to securely register and log in, create and manage their tasks, update task status, and organize their work through a simple and responsive dashboard.

## 🚀 Features

* 🔐 **User Authentication** — Secure registration and login using JWT authentication
* 📝 **Task Management** — Create, view, update, and delete tasks
* 📊 **Task Dashboard** — Manage and track tasks from a centralized dashboard
* 🔒 **Protected Routes** — Authenticated access to user-specific task data
* 🗄️ **MongoDB Database** — Persistent storage for users and tasks
* 🌐 **RESTful APIs** — Backend APIs for authentication and task management
* 📱 **Responsive Design** — Works across desktop and mobile devices
* ⚡ **Modern UI** — Built with React and Tailwind CSS

## 🛠️ Technologies Used

### Frontend

* React.js
* JavaScript
* Tailwind CSS
* Axios
* React Router DOM
* Vite

### Backend

* Node.js
* Express.js
* REST APIs
* JWT Authentication
* Middleware

### Database

* MongoDB
* Mongoose
* MongoDB Atlas

### Tools

* Git
* GitHub
* Postman
* NPM
* VS Code

## 📁 Project Structure

```text
TaskFlow/
├── Frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── ...
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kunalmahor05/TaskFlow--Task-Management-App.git
cd TaskFlow
```

### 2. Install Dependencies

Install frontend dependencies:

```bash
cd Frontend
npm install
```

Install backend dependencies:

```bash
cd ../backend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the `backend` folder:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET_KEY=your_jwt_secret_key
```

Replace the values with your own MongoDB connection string and JWT secret.

### 4. Start the Backend

```bash
cd backend
npm run dev
```

The backend will run on:

```text
http://localhost:8000
```

### 5. Start the Frontend

Open another terminal:

```bash
cd backend
npm run dev
```

The frontend will run on the Vite development server.

## 🔑 Authentication

TaskFlow uses **JSON Web Tokens (JWT)** for authentication. After successful login, the authenticated user can access protected task-management functionality. Middleware is used on the backend to verify authentication before allowing access to protected routes.

## 📌 Main Functionalities

### Authentication

* User registration
* User login
* JWT token generation
* Protected routes
* Logout functionality

### Task Management

* Create tasks
* View tasks
* Update tasks
* Delete tasks
* Manage task status

## 🎯 Purpose

The project was developed to gain practical experience in **full-stack web development** and understand how frontend, backend, authentication, APIs, and databases work together in a real-world application.

## 👨‍💻 Author

**Kunal Mahor**

B.Tech Computer Science Engineering
AKTU — Dr. A.P.J. Abdul Kalam Technical University

---

⭐ If you found this project useful, consider giving the repository a star!

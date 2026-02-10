# SumitTech Solutions 🚀

**SumitTech Solutions** is a dynamic IT service platform built on the MERN stack (MongoDB, Express.js, React.js, Node.js). It features secure JWT authentication, a responsive UI, and a powerful Admin Dashboard for managing users and services. This project demonstrates expertise in full-stack development and delivering modern web solutions.

## 🌟 Features

- **Full Authentication System**: Secure Login and Registration using JWT and Bcrypt.
- **Admin Dashboard**: Manage users, contacts, and services efficiently (CRUD operations).
- **Responsive Design**: Built with modern CSS for a seamless experience on all devices.
- **Service Management**: Dynamic listing of IT services fetched from the database.
- **Contact Form**: Integrated contact form for user inquiries.
- **Secure Backend**: Robust API with input validation using Zod.

## 🛠️ Tech Stack

- **Frontend**: React.js, Vite, React Router DOM, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JSON Web Tokens (JWT)
- **Validation**: Zod

## ⚙️ Environment Variables Setup (.env)

To run this project, you need to configure environment variables in both the **Server** and **Client** folders. Follow the instructions below:

### 1. Server Environment Variables (`server/.env`)
Create a `.env` file inside the `server` folder and add the following variables:

```env
PORT=3000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/your_db_name
JWT_SECRET_KEY=your_super_secret_random_key_here
```

*   **PORT**: Port number on which the backend server will run.
*   **MONGODB_URI**: MongoDB connection string (MongoDB Atlas or Localhost).
*   **JWT_SECRET_KEY**: A strong secret key used for JWT token generation.  (e.g., `mysupersecretkey123`).

### 2. Client Environment Variables (`client/.env`)
Inside the `client` directory, create a .`env` file and add:

```env
VITE_BACKEND_URL=http://localhost:3000
```

*   **VITE_BACKEND_URL**: Backend server URL.
If running locally, use http://localhost:3000.

## 🚀 Installation & Run Guide

Follow the steps below to run the project on your local machine.

### Step 1: Clone the Repository
```bash
git clone <repository-url>
cd "Web Development By SumitTech Solutions"
```

### Step 2: Backend Setup
Open a terminal and navigate to the server directory:
```bash
cd server
npm install
npm run dev
```
*The backend server will start at:`http://localhost:3000` *

### Step 3: Frontend Setup
Open a new terminal and navigate to the client directory:
```bash
cd client
npm install
npm run dev
```
*The frontend application will start at: http://localhost:5173 (or a similar available port) *

---
Created with ❤️ by **Sumit**
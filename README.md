# StaffSync – Smart HR Management System

StaffSync is a MERN-stack based Human Resource Management platform designed to simplify employee management, attendance tracking, leave administration, and workplace communication through a centralized dashboard.

## 🌐 Live Deployment

**Frontend:** [https://staff-sync-three.vercel.app/](https://staff-sync-three.vercel.app/)

**Backend API:** [https://staffsync-1uaq.onrender.com](https://staffsync-1uaq.onrender.com)

## ✨ Key Features

- **User Authentication:** Secure registration and login using JWT authentication.
- **Role-Based Access:** Separate permissions for HR, Managers, and Employees.
- **Employee Management:** View and manage employee records through the HR dashboard.
- **Attendance Tracking:** Check-in, check-out, and view attendance history.
- **Leave Management:** Submit leave applications and manage approval or rejection workflows.
- **Announcements:** HR can publish announcements for all registered users.
- **API Health Monitoring:** Backend health-check endpoint for service status.

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React, JavaScript, HTML, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JSON Web Tokens (JWT) |
| Deployment | Vercel (Frontend), Render (Backend) |

## 💻 Run Locally

### Prerequisites
- Node.js (LTS version)
- npm
- MongoDB local instance or MongoDB Atlas
- Git

### 1. Clone the repository

```bash
git clone https://github.com/anshika-j30/StaffSync.git
cd StaffSync
```

### 2. Configure and start the backend

```bash
cd server
npm install
```

Create a `.env` file using `.env.example` as a reference and configure:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_secret
CLIENT_ORIGIN=http://localhost:5173
```

Start the backend:

```bash
npm run dev
```

The backend will run at `http://localhost:5000`.

### 3. Configure and start the frontend

Open another terminal:

```bash
cd client
npm install
npm run dev
```

Open the local Vite URL displayed in your terminal, usually `http://localhost:5173`.

## 📁 Project Structure

```text
StaffSync/
├── client/       # React frontend application
├── server/       # Express backend and API
├── .gitignore
└── README.md
```

## 🔐 Security & Limitations

StaffSync is currently developed as a functional MVP for demonstration and portfolio purposes.

Before production use, additional improvements are recommended, including stronger role provisioning, email verification, password recovery, audit logging, automated testing, and a comprehensive security review.

The current demo uses localStorage for JWT storage and includes role selection during registration. Public HR account creation should be restricted before production deployment.

## 👩‍💻 Project

**StaffSync – Functional MERN MVP**

A centralized HR management solution built using the MERN stack, with separate user roles and essential workforce management features.

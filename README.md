# 🏥 CareFlow Hospital Management System

> A modern hospital administration platform built with **React + Vite** and an **Express REST API**, designed to manage patients, doctors, appointments, pharmacy, laboratory services, rooms, billing, and medical records.

## 🧩 Architecture

```text
React + Vite Frontend
        │
        ▼
Express REST API
        │
        ▼
PostgreSQL Database
```

The project is organized as a separate frontend and backend application. The frontend uses React 18 with Vite and Lucide icons, while the server provides the Express API, authentication, and PostgreSQL connectivity. fileciteturn14file0L2-L2 fileciteturn15file0L2-L2

## 🩺 Hospital Modules

| Module | What it manages |
|---|---|
| 📊 Dashboard | Hospital overview and key information |
| 🧑‍⚕️ Patients | Registration, search, and patient information |
| 👨‍⚕️ Doctors | Doctor records and management |
| 📅 Appointments | Appointment scheduling and tracking |
| 💊 Pharmacy | Medicine and inventory management |
| 🧪 Laboratory | Tests and laboratory workflow |
| 🛏️ Rooms & Beds | Room and bed availability |
| 💳 Billing | Hospital billing information |
| 📋 Medical Records | Patient medical history and records |

## ⚡ Technology Stack

### Frontend
- **React 18**
- **Vite 6**
- **Lucide React**
- Modern component-based UI

### Backend
- **Node.js**
- **Express.js**
- **JWT authentication**
- **bcryptjs** for password hashing
- **CORS**
- **dotenv**

### Database
- **PostgreSQL** via `pg`

The actual client and server package definitions confirm this React/Vite + Express/PostgreSQL architecture. fileciteturn14file0L2-L2 fileciteturn15file0L2-L2

## 🚀 Run the Project

### 1. Clone

```bash
git clone https://github.com/Harsh0675/Hospital-Management-System.git
cd Hospital-Management-System
```

### 2. Install dependencies

```bash
npm install
npm run install:all
```

### 3. Start development mode

```bash
npm run dev
```

The configured development servers are:

```text
Frontend → http://localhost:5173
API      → http://localhost:5000
```

The root project provides `install:all`, `dev`, and `start` scripts for the client/server workflow. fileciteturn13file0L2-L2

## 🔐 Demo Account

```text
Email:    admin@careflow.local
Password: admin123
```

This account is for demonstration/development purposes only.

## 🌐 GitHub Pages

The frontend is configured for GitHub Pages deployment through the repository's Pages workflow. Because GitHub Pages is static hosting, the Express API requires a separate Node.js-capable hosting service.

## 🔒 Security & Privacy

This project is intended for **development/demo use**.

- Use synthetic patient data for demonstrations.
- Never commit real medical records.
- Never commit production passwords, API keys, or database credentials.
- Configure secrets through environment variables.

## 📁 Repository Structure

```text
Hospital-Management-System/
├── client/                 # React + Vite frontend
│   ├── src/
│   └── package.json
├── server/                 # Express + PostgreSQL backend
│   ├── src/
│   └── package.json
├── .github/
│   └── workflows/          # GitHub Pages workflow
├── package.json             # Root development scripts
└── README.md
```

## 🎯 Project Goal

CareFlow demonstrates how a modern full-stack healthcare administration system can be structured using a **React frontend, REST API backend, authentication, and PostgreSQL database**.

## 👨‍💻 Author

**Harsh**

GitHub: https://github.com/Harsh0675

## 📄 License

See the repository license for usage terms.

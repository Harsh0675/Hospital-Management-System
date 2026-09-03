# 🏥 CareFlow Hospital Management System

> A full-stack hospital administration platform built with React, Express, and PostgreSQL.

CareFlow models a real healthcare operations workflow across patients, doctors, appointments, pharmacy, laboratory services, rooms and beds, billing, and medical records.

## Architecture

```text
React 18 + Vite
      │
      ▼
Express REST API
      │
      ▼
PostgreSQL
```

Authentication uses JWT with bcryptjs for password hashing. The frontend and backend are maintained as separate applications.

## 🩺 Core Modules

| Module | Purpose |
|---|---|
| Dashboard | Operational overview |
| Patients | Registration, search, and records |
| Doctors | Doctor management |
| Appointments | Scheduling and tracking |
| Pharmacy | Medicine and inventory workflows |
| Laboratory | Test and lab workflows |
| Rooms & Beds | Availability management |
| Billing | Billing workflows |
| Medical Records | Patient history and records |

## ⚙️ Technology

**Frontend:** React 18, Vite 6, Lucide React  
**Backend:** Node.js, Express, JWT, bcryptjs, CORS, dotenv  
**Database:** PostgreSQL via `pg`

## 🚀 Local Development

```bash
git clone https://github.com/Harsh0675/Hospital-Management-System.git
cd Hospital-Management-System
npm install
npm run install:all
npm run dev
```

Development services:

```text
Frontend → http://localhost:5173
API      → http://localhost:5000
```

## 🔐 Demo Login

```text
Email:    admin@careflow.local
Password: admin123
```

For demonstration/development only. Do not use this credential in production.

## 🔒 Security & Privacy

This repository is a software-development demonstration, **not a production medical-record system**.

- Use synthetic data only.
- Never commit real patient information.
- Keep passwords, database credentials, and API keys in environment variables.
- Apply appropriate healthcare privacy, authentication, authorization, auditing, encryption, and compliance controls before any real-world deployment.

## 📁 Structure

```text
Hospital-Management-System/
├── client/                 # React + Vite frontend
├── server/                 # Express + PostgreSQL API
├── .github/workflows/      # Automation / deployment workflows
├── package.json            # Root scripts
└── README.md
```

## 🎯 Engineering Value

CareFlow demonstrates multi-module product design, frontend/backend separation, REST API integration, authentication, relational persistence, and healthcare-domain workflow modeling.

## 👨‍💻 Author

**Harsh** — [GitHub](https://github.com/Harsh0675)

## 📄 License

See the repository license for usage terms.

# CareFlow Hospital Management System

A full-stack Hospital Management System with a React/Vite frontend and Express API.

## Features
- Dashboard
- Patient registration and search
- Doctors
- Appointments
- Pharmacy inventory
- Laboratory tests
- Rooms and beds
- Billing
- Medical records
- REST API
- PostgreSQL-ready schema
- Demo JSON persistence

## Demo
Email: `admin@careflow.local`
Password: `admin123`

## Local run
Node.js 18+ is recommended.

```bash
npm install
npm run install:all
npm run dev
```

Frontend: `http://localhost:5173`
API: `http://localhost:5000`

## GitHub Pages
The frontend is configured for GitHub Pages deployment through `.github/workflows/pages.yml`. The Pages build is a static frontend; backend API deployment requires a separate Node hosting service.

Use synthetic/demo patient information only. Never commit real medical records, passwords, API keys, or production secrets.
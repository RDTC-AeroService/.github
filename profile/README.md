# Aero Services ✈️

Aviation Training and Payroll Support Website

<img src="https://i.pinimg.com/originals/f0/7d/ff/f07dff6966ac48982773fbb149bfde48.gif">

## 📌 Overview

Aero Services is a web application designed to centralize aviation staff management, payroll processing, and training operations. The platform aims to improve efficiency, data accuracy, and accessibility for HR teams, management, and employees.

## 🎯 Objectives

- Centralize staff information.
- Automate payroll workflows.
- Improve training and certification tracking.
- Strengthen security and controlled access.
- Provide reporting and analytics.
- Improve operational efficiency and compliance readiness.

## 👥 User Roles

### 🛡️ Admin

- Full system access.
- Manage users and permissions.
- Approve payroll and training records.

### 🧑‍💼 HR Manager

- Manage employee profiles.
- Manage payroll configuration and processing.
- Create training programs and schedules.
- Generate HR and compliance reports.

### 👨‍✈️ Employee

- View personal profile information.
- View payroll history and payment receipts.
- Register for training.
- View certifications and status.

## 🚀 Core Features

### 🧾 Staff Profile Management

- Employee registration with auto-generated ID and profile photo upload.
- Personal data: full name, date of birth, gender, nationality, ID/passport, marital status.
- Contact data: phone, email, address, emergency contact.
- Job data: position, department, employment type, start/end date, reporting manager.
- Employment history: previous roles, promotion history, salary history.
- Skills and qualifications: education, certifications, skills, languages.
- Document management: secure upload/download for contracts, IDs, certificates.
- Search and filtering by employee name and department.

### 💰 Payroll Management

- Salary configuration: base salary, allowances, deductions, taxes.
- Attendance support: clock in/out, monthly summary, late tracking, leave integration.
- Overtime workflow: entry, approval, rate setup, auto-calculation.
- Bonus handling: performance, project, and manual bonuses.
- Net salary computation: salary, overtime, bonuses, allowances, deductions.
- Payment receipts: monthly generation, download, and email distribution.
- Reports: monthly payroll, department summaries, annual overview.

### 🎓 Training Management

- Training program creation with schedule, trainer, and location.
- Course registration by employee or HR with optional approval workflow.
- Schedule management with reminders and attendance tracking.
- Skill tracking after training and skill-gap visibility.
- Certification records with expiry and renewal reminders.
- Training evaluation via feedback and effectiveness reporting.

## 🗂️ Current Repository Structure

This workspace currently contains the frontend application:

```text
aero-service/
├── frontend/
├── backend/
├── .env                        # Local environment variables (git ignore)
├── .env.example                # Env vars template
├── docker-compose.yml          # Docker setup for DB, backend, frontend
├── README.md
└── LICENSE                     # Optional
```

## 🛠️ Tech Stack

- Frontend: Next.js (App Router), React, TypeScript
- Styling: CSS (`frontend/app/globals.css`)
- Planned backend (not present in this workspace yet): NestJS + MySQL

## ✅ Prerequisites

- Node.js 18+
- pnpm
- Git

## ⚡ Getting Started (Frontend)

From the repository root:

```bash
cd frontend
pnpm install
pnpm dev
```

Open `http://localhost:3000` in your browser.

### 🔁 Alternative package managers

```bash
# npm
cd frontend
pnpm install
pnpm run dev
```

## 🔐 Environment Variables

If you connect this frontend to an API later, create `frontend/.env.local`:

```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

## 🪧 Figma

- Prototype: [https://www.figma.com/design/9oY3qd8p2hMmjIlovoNA9K/RDTC-Prototype?node-id=0-1&p=f&t=46KgtfWy9B3vznno-0]
- System Flows: [https://www.figma.com/board/Z6uI657wYDM02vr8zENwNb/RDTC-Flow-Chart?node-id=0-1&p=f&t=bvOV1f9VwH3GKIRx-0]

## 🗺️ Roadmap

- Add backend service (`backend/`) for auth, staff, payroll, and training modules.
- Add database schema and migrations.
- Add role-based access control.
- Add automated testing and CI/CD pipeline.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add: your feature"`
4. Push your branch: `git push origin feature/your-feature`
5. Open a pull request.

## 📄 License

This project is licensed under the MIT License.

## 📬 Contact

For questions or support, reach out to 
- [victorkhornkh@gmail.com]
- [benbunnaka@gmail.com]


# LeXora
A digital justice platform connecting verified lawyers with citizens seeking legal assistance, inspired by marketplace models like InDrive.

## Project Overview
Lexora is a legal-tech application that provides citizens easy access to verified lawyers for legal consultation, issue reporting, and case tracking. I'm trying to design this platform to be scalable, secure, and user-friendly, with role-based dashboards for both users and lawyers.

This project is perfect for citizens seeking legal assistance.
---

## Key Features
- **User Module**
  - Sign Up / Sign In with email and password
  - Profile setup and management
  - Report legal issues
  - Hire lawyers and track cases
  - Secure logout

- **Lawyer Module**
  - Verified lawyer Sign Up / Sign In
  - Upload and verify Bar registration, CNIC, and certificates
  - Dashboard for managing cases
  - Profile and document management
  - Role-based access control

- **Security & Authentication**
  - Password hashing (bcrypt)
  - JWT token-based sessions
  - Role-based login (User / Lawyer / Admin)
  - Validation of user and lawyer information

- **Admin Module (Future)**
  - Verify lawyer accounts
  - Approve / reject submissions
  - Manage platform content

---

## Planned Tech Stack

- **Frontend:** React / Next.js, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB / PostgreSQL  
- **Authentication:** JWT, bcrypt  
- **File Storage:** Local / Cloud storage (for documents)  
- **Version Control:** Git  

---

## Folder Structure
```bash
lexora/
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   │   ├── database.js
│   │   │   ├── auth.js
│   │   │
│   │   ├── models/
│   │   │   ├── User.js
│   │   │   ├── Lawyer.js
│   │   │   ├── Verification.js
│   │   │
│   │   ├── controllers/
│   │   │   ├── authController.js
│   │   │   ├── userController.js
│   │   │   ├── lawyerController.js
│   │   │
│   │   ├── routes/
│   │   │   ├── authRoutes.js
│   │   │   ├── userRoutes.js
│   │   │   ├── lawyerRoutes.js
│   │   │
│   │   ├── middlewares/
│   │   │   ├── authMiddleware.js
│   │   │   ├── roleCheck.js
│   │   │
│   │   ├── utils/
│   │   │   ├── validators.js
│   │   │   ├── fileUpload.js
│   │   │
│   │   └── app.js
│   │
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── auth/
│   │   │   │   ├── Login.jsx
│   │   │   │   ├── SignupUser.jsx
│   │   │   │   ├── SignupLawyer.jsx
│   │   │
│   │   │   ├── dashboard/
│   │   │   │   ├── UserDashboard.jsx
│   │   │   │   ├── LawyerDashboard.jsx
│   │   │
│   │   ├── services/
│   │   │   └── api.js
│   │   │
│   │   ├── hooks/
│   │   └── App.jsx
│
├── docs/
│   ├── flowcharts/
│   ├── system-design.md
│
├── README.md
└── .env.example
```
### Clone the Repository
```bash
git clone https://github.com/TahiraNawab123/lexora
```
# Install Dependencies
```bash 
cd backend
npm install
cd ../frontend
npm install
Run the Project
```
# Backend
```bash
cd backend
npm run dev
```
# Frontend
```bash
cd frontend
npm run dev
```
# Project Goals
- Build a fully functional, role-based authentication system
- Provide verified legal assistance platform for citizens
- Learn file verification, JWT authentication, and dashboard management
- Build a professional, portfolio-ready project
- Future Improvements
- Case management and tracking system
- Lawyer-client chat module
- Payment integration for lawyer services
- AI-based legal assistant
- Mobile app version
- Dark / Light theme support

# About
Lexora is a student-led legal-tech initiative focused on empowering citizens and connecting them with verified legal professionals efficiently and securely.
 
#made by Tahira Nawab


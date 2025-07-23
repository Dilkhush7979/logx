# 🚀 EntryLogX - Premium Visitor Gate Pass System (by Dilkhush)

A full-featured visitor management system with admin login, QR-based verification, and real-time security scanning.

## 🧩 Features
- Visitor Entry Form (Name, Phone, Purpose, To Meet)
- QR Code generated for each visitor
- Admin Panel: View + Approve/Reject visitors
- Security Panel: Scan QR and verify instantly
- Auto force-approval after 10 minutes if no action
- SQLite Backend (FastAPI) – Easy to host or extend

## 🛠 Tech Stack
- Frontend: HTML + Tailwind CSS
- Backend: FastAPI + SQLite
- QR Generator: Python qrcode + Pillow
- Security Scanner: html5-qrcode.js (browser-based)

## 🏁 How to Run

### 1. Install Dependencies
```bash
cd backend
pip install -r requirements.txt
```

### 2. Run Server
```bash
uvicorn main:app --reload
```

### 3. Open Pages
- `http://localhost:8000` - Visitor Form
- `http://localhost:8000/admin` - Admin Panel (Login)
- `http://localhost:8000/security` - Security QR Scanner

## 🧠 Default Admin Login
- **Username:** admin
- **Password:** entry123

## 📂 Folder Structure
- `/frontend` - HTML Files
- `/backend` - FastAPI App + QR + DB
- `/generated_qr` - QR Code Images

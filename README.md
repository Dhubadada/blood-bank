# 🩸 Blood Bank Management System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-lightgrey)
![SQLite](https://img.shields.io/badge/SQLite-3-green)

A web-based blood donation management system with admin dashboard, donor registration, and blood request tracking.

## ✨ Features
- **Admin Dashboard** (Manage donors, volunteers, and requests)
- **Donor Registration** (Track blood types and donation history)
- **Blood Request System** (Priority-based allocation)
- **Email Notifications** (For new requests/donations)
- **Responsive Design** (Works on mobile/desktop)

## 🚀 Quick Start
```bash
# 1. Clone repository
git clone https://github.com/Dhubadada/blood-bank.git
cd blood-bank
# 2. Install dependencies
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

# 3. Run application
python app.py
Access at: http://localhost:5000
 Admin Access
URL: /admin/login

Default Credentials:
Username: admin | Password: admin123 (Change in production!)
matri-blood-bank/
├── venv/
├── templates/
│   ├── admin/
│   │   ├── login.html
│   │   ├── dashboard.html
│   │   ├── donors.html
│   │   ├── volunteers.html
│   │   ├── requests.html
│   │   └── messages.html
│   ├── index.html
│   ├── about.html
│   ├── services.html
│   ├── blood_request.html
│   ├── donor.html
│   ├── volunteer.html
│   ├── contact.html
│   └── appointment.html
├── static/
│   └── img/
│       └── matri.png
├── app.py
├── schema.sql
├── requirements.txt

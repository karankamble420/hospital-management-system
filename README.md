# 🏥 Hospital Management System

![developer](https://img.shields.io/badge/Developed%20By%20%3A-Karan%20Kamble-blue)

---

## 📸 Screenshots

### Homepage
![homepage](static/screenshots/homepage.png)

### Admin Dashboard
![admin dashboard](static/screenshots/admin_dashboard.png)

### Invoice
![invoice](static/screenshots/invoice.png)

### Doctor List
![doctor list](static/screenshots/admin_doctor.png)

---

## 🚀 Project Overview

A **Django-based Hospital Management System** that manages:
- Doctors
- Patients
- Appointments
- Billing & Invoice generation
- Admin approval workflows

This project demonstrates **real-world hospital workflows** with role-based access control.

---

## 👤 User Roles & Features

### 🔐 Admin
- Signup & Login (no approval required)
- Add / View / Approve / Reject / Delete doctors
- Admit / View / Approve / Reject / Discharge patients
- Generate & Download Invoice (PDF)
- View / Book / Approve appointments

---

### 🩺 Doctor
- Apply for job (Admin approval required)
- View assigned patients
- View discharged patients
- View appointments
- Delete appointments after consultation

---

### 🧑‍⚕️ Patient
- Signup & Login (Admin approval required)
- View assigned doctor details
- Book appointments
- View appointment status
- View & download invoice after discharge

---

## ⚙️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite
- **PDF Generation:** xhtml2pdf
- **Authentication:** Django Auth + Groups
- **Version Control:** Git & GitHub

---

## ▶️ How to Run This Project

### 1️⃣ Install Requirements
```bash
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
 
run this
python manage.py makemigrations
python manage.py migrate

run this
python manage.py runserver

open brower
http://127.0.0.1:8000/


📧 Contact Us Page Setup

Update these values in settings.py:

EMAIL_HOST_USER = 'your_email@gmail.com'
EMAIL_HOST_PASSWORD = 'your_app_password'
EMAIL_RECEIVING_USER = 'your_email@gmail.com'

👨‍💻 Developed By

Karan Kamble


---

# ✅ PART 2: COMMIT & PUSH CHANGES TO GITHUB

Now let’s **save this change in Git**.

### 🔹 Step 1: Save file
Press **Ctrl + S**

---

### 🔹 Step 2: Check Git status
```bash
git status
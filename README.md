# Django Authentication System 🔑

A simple **Login, Registration, and Logout** system built using Django.  
This project demonstrates how to implement user authentication using Django’s built-in `auth` module.

---

## 🚀 Features
- User Registration (with password confirmation)
- User Login
- User Logout
- Session-based authentication
- Validation for duplicate usernames & password mismatch
- Simple UI with Django Templates

---

## 📂 Project Structure
authsystem/
│── accounts/ # Django app for authentication
│ ├── templates/accounts # HTML templates (login, register, home)
│ ├── urls.py # App-specific URLs
│ └── views.py # Authentication logic
│
│── authsystem/ # Main Django project folder
│ ├── settings.py # Project settings
│ └── urls.py # Main URLs
│
│── manage.py # Django management script

---

## ⚙️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/MithunGowda67/django-auth-system.git
cd django-auth-system

2. INSTALL DEPENDENCIES
pip install django
3. Apply Migrations
python manage.py migrate
4. RUN SERVER
python manage.py runserver

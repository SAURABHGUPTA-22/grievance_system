# 📢 Grievance Handling System

A full-stack Django-based web application to streamline the submission, tracking, escalation, and resolution of grievances within an organization. This system supports role-based access,
real-time grievance updates, feedback collection, data visualization, and report export.

## 🚀 Features

- 📝 *Submit Grievances*
- 👥 *Role-Based Dashboards* for Admin, Employee, and Customer
- ⚙ *Admin Panel for Department & Grievance Assignment*
- ⏱ *Automatic Escalation* of unresolved grievances after 2 days
- ⭐ *Feedback Submission* with rating & comment after resolution
- 📊 *Dashboard Analytics* with Charts
- 📄 *Filtered Reports & CSV Export* for Admins

---

## 🔧 Tech Stack

- *Backend:* Python, Django
- *Frontend:* HTML5, CSS3, Bootstrap 5, JavaScript
- *Database:* SQLite3
- *Visualization:* Chart.js
- *Version Control:* Git, GitHub
- *IDE/Tools:* Visual Studio Code

---

## ⚙ Setup Instructions

Make sure Django 5.1 or higher and MySQL is installed. 

1. *Clone Repository*
```bash
git clone https://github.com/SAURABHGUPTA-22/grievance_system.git
cd grievance-handling-system
```
2. Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```
3. Dependencies
```bash
pip install djangorestframework
pip install django-cors-headers
```
4. Run Development Server
```bash
python manage.py runserver
```
5. Users-  
   You can create customers and Employees easily, and for Admins one Admin superuser is already made(username: Admin; Pass: 1234pass).
   To create more Admin users one can create manually or can go to <a href="http://127.0.0.1:8000/register-admin">Register Admin<a/> when you are logged in as admin to register New Admin.
---

## 🙌 Acknowledgements


*Django Documentation* – https://docs.djangoproject.com/

*Bootstrap* – https://getbootstrap.com/

*Chart.js* – https://www.chartjs.org/

---

## 👀 Demo Outputs

![Login ](https://github.com/user-attachments/assets/093e7f9b-17f4-4216-9ae8-a71ecedc1e9a)

![Customer - Submission ](https://github.com/user-attachments/assets/9b300803-369c-4f2b-9773-0241230d5a79)

![Admin - 2](https://github.com/user-attachments/assets/f7149b53-069e-4e85-958e-abdf4a0a8757)

![Admin - Grievance Table ](https://github.com/user-attachments/assets/090a2ee2-0cf9-4a39-af71-3c0134a5ab00)

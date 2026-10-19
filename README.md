# 🏫 School Management System

A web-based School Management System developed using **Python and Django** to provide a foundation for managing school-related information and administrative tasks.

## 📌 Project Overview

The School Management System is a Django-based web application designed to simplify school administration. It uses Django's built-in admin interface and an SQLite database, with scope for adding more school management features.

## 🛠️ Technologies Used

- **Backend:** Python
- **Framework:** Django
- **Database:** SQLite
- **Frontend:** Django Templates (where implemented)
- **Development Tool:** Visual Studio Code
- **Version Control:** Git and GitHub

## ✨ Features

- Django project setup and configuration
- Django admin interface
- SQLite database integration
- School application structure
- Foundation for extending school management functionality

*Note: Add features such as student registration, attendance, teacher management, and fee tracking only after implementing them in the project.*

## 📂 Project Structure

```text
school_management/
├── manage.py
├── requirements.txt
├── school/
├── school_project/
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Chyaitanya12/school_management.git
cd school_management
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
```

### 3. Activate the virtual environment

**macOS / Linux:**

```bash
source .venv/bin/activate
```

**Windows:**

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Create an administrator account

```bash
python manage.py createsuperuser
```

Follow the prompts to create your username and password.

### 7. Start the development server

```bash
python manage.py runserver
```

Open the following address in your browser:

http://127.0.0.1:8000/

To access the Django administration panel, visit:

http://127.0.0.1:8000/admin/

## 🚀 Future Enhancements

- Student registration and profile management
- Teacher and staff management
- Attendance tracking
- Class and subject management
- Fee management
- Reports and dashboards

These are possible future improvements, not claims about existing functionality.

## 🎯 Project Objective

The objective of this project is to develop practical skills in Python, Django, database integration, and web application development while building a foundation for a school administration system.

## 👨‍💻 Author

**Chyaitanya**

GitHub: [@Chyaitanya12](https://github.com/Chyaitanya12)

## 📄 License

This project is available for educational and learning purposes. Add a formal open-source license if you intend to distribute it under specific reuse terms.

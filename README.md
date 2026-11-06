# Student Management System

A simple Django-based Student Management System for managing student records with add, view, update, and delete functionality.

## Features

- Add new students
- View all student records
- Edit student details
- Delete student records
- Search and filter students in the Django admin
- SQLite database setup by default

## Project Structure

```text
student_management_system_django_project/
├── student_management_system/
│   ├── manage.py
│   ├── db.sqlite3
│   ├── students/
│   └── student_management_system/
├── venv/
├── README.md
└── .git/
```

## Requirements

- Python 3.10+
- Django 6.1.2
- Virtual environment (recommended)

## Setup Instructions

1. Open a terminal in the project root.
2. Activate the virtual environment:

   Windows PowerShell:
   ```powershell
   .\venv\Scripts\Activate.ps1
   ```

3. Navigate to the Django project folder:

   ```powershell
   cd .\student_management_system
   ```

4. Apply migrations:

   ```powershell
   python manage.py migrate
   ```

5. Create a superuser (optional, for admin access):

   ```powershell
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```powershell
   python manage.py runserver
   ```

7. Open the app in the browser:

   ```text
   http://127.0.0.1:8000/
   ```

8. Django admin is available at:

   ```text
   http://127.0.0.1:8000/admin/
   ```

## Default App Behavior

The app includes:
- a student list page
- add-student form
- edit-student form
- delete confirmation page

## Notes

This project uses the default Django SQLite database configuration and is ready for local development and testing.

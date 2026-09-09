# Student Portal

A Django-based student portal developed with Python to provide a structured web interface for managing and presenting student-related information.

## Overview

The **Student Portal** is a web application built using the Django framework. The project demonstrates the development of a basic web-based portal using Django's project and application structure, URL routing, views, templates, and SQLite database.

The project is structured into separate Django components, including the main `student_portal` project and the `dashboard` and `student_dashboard` applications.

## Features

### Home Page

The portal includes a home page that serves as the main entry point of the application.

### About Page

An About page is included to provide information about the portal.

### Django Application Structure

The project demonstrates how a Django application can be divided into different components for better organization and maintainability.

### Template-Based Pages

The application uses Django templates to render the web pages, including the Home and About pages.

### SQLite Database

The project includes a SQLite database for local development and data storage.

## Technologies Used

* **Python**
* **Django**
* **SQLite**
* **HTML**
* **Django Templates**

## Project Structure

```text
student-portal/
│
├── dashboard/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── student_dashboard/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── student_portal/
│   ├── templates/
│   │   ├── home.html
│   │   └── about.html
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── .gitignore
├── db.sqlite3
└── manage.py
```

## How It Works

The application follows Django's standard architecture.

The `student_portal` directory contains the main Django project configuration, including settings, URL configuration, and WSGI/ASGI configuration.

The `dashboard` application contains Django application files such as models, views, URLs, migrations, and administration configuration.

The `student_dashboard` application is another Django application within the project and is configured using Django's `AppConfig`.

The application uses Django views to render HTML templates. For example, the dashboard application contains views that render the `home.html` and `about.html` templates.

## Getting Started

### Prerequisites

Before running the project, make sure you have:

* Python 3 installed
* pip installed
* Git installed

### 1. Clone the Repository

```bash
git clone https://github.com/Ndukuu/student-portal.git
```

### 2. Navigate into the Project

```bash
cd student-portal
```

### 3. Create a Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Django

```bash
pip install django
```

### 5. Run Migrations

```bash
python manage.py migrate
```

### 6. Start the Development Server

```bash
python manage.py runserver
```

The application will normally be available at:

```text
http://127.0.0.1:8000/
```

## Learning Objectives

This project was developed to strengthen practical understanding of:

* Django project structure
* Python web development
* Django applications
* URL routing
* Views and templates
* SQLite database integration
* Django migrations
* Basic web application development
* Organizing a project into reusable components

## Future Improvements

The portal can be expanded into a more complete student management system by adding features such as:

* Student registration and authentication
* Student profiles
* Course and unit management
* Academic results
* Timetables
* Attendance tracking
* Assignment management
* Announcements
* Student dashboard statistics
* Lecturer/admin management
* Database-backed student records
* Role-based access control
* Improved UI/UX
* Automated testing

## Project Status

This project is a **Django learning and development project** and can be further expanded into a fully functional student management platform.

## Author

**Lianne Murgor**

Business Information Technology Student
Strathmore University

GitHub: [Ndukuu](https://github.com/Ndukuu)


# Django User Login Authentication System

![Django](https://img.shields.io/badge/Django-v3.2-green.svg) 
![License](https://img.shields.io/badge/license-MIT-blue.svg) 
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg) 
![Contributions](https://img.shields.io/badge/contributions-welcome-orange.svg)

Welcome to the **Django User Login Authentication** system, created by **Aliza Hashmat**. This project is a foundational web application built with **Django**, focusing on user registration, login, logout, and session management.

---

## 🛠️ Features

- **User Registration**: Users can create an account by registering with an email and password.
- **User Login**: Secure login functionality with session handling.
- **User Logout**: Users can log out securely, ending their session.
- **User Authentication**: Only authenticated users can access protected routes.
- **Responsive Design**: Includes basic HTML templates for login, registration, and user dashboard.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AlizaHashmat-eng/django-user-login-authentication.git
cd django-user-login-authentication
```

### 2. Set Up a Virtual Environment

Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
```

### 3. Install Dependencies

Install the required dependencies from `requirements.txt` (if applicable):

```bash
pip install django
```

### 4. Migrate the Database

Apply the migrations to set up the database:

```bash
python manage.py migrate
```

### 5. Run the Application

Start the Django development server:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000` to view the application.

---

## 📦 Project Structure

```plaintext
django-user-login-authentication/
├── authentication/            # App folder
│   ├── __init__.py
│   ├── admin.py               # Admin interface
│   ├── apps.py                # App configuration
│   ├── models.py              # Database models
│   ├── views.py               # View functions (login, logout, register)
│   ├── urls.py                # URL routing for authentication
│   └── templates/             # HTML templates
│       ├── base.html          # Base template
│       ├── index.html         # Homepage template
│       ├── about.html         # About page
│       ├── contact.html       # Contact page
│       └── services.html      # Services page
├── manage.py                  # Django management script
├── db.sqlite3                 # SQLite database
├── static/                    # Static files (images, CSS)
│   ├── carousel1.jpeg
│   ├── carousel2.jpeg
│   └── carousel3.jpeg
├── LICENSE                    # License file
└── README.md                  # Project documentation
```

---

## 📋 Dependencies

- **Django**: Python web framework for rapid development.
- **SQLite**: Default database for Django (used for development).

Install dependencies using:

```bash
pip install django
```

---

## 🛠️ Authentication Workflow

1. **Registration**: Users can sign up with their email and password.
2. **Login**: Registered users can log in with their credentials.
3. **Logout**: Logged-in users can securely log out.
4. **Protected Routes**: Only authenticated users can access certain views (e.g., user dashboard).

---

## 🖼️ Application Pages

- **Home Page**: Displays the main homepage with links to login and register.
- **About Page**: Static about page template.
- **Contact Page**: Static contact page template.
- **Services Page**: Displays available services.
  
---

## 🛠️ Deployment

To deploy the Django application, follow these steps:

1. **Configure the Application**: Update settings for the production environment (e.g., allowed hosts, database configuration).
2. **Apply Migrations**: Run migrations to set up the production database.
3. **Deploy on Heroku (or any hosting service)**: Use Heroku CLI or other tools to deploy the application.

---

## 📧 Contact

This project is developed and maintained by **Aliza Hashmat**.  
For any questions or feedback, feel free to contact me via email: [aliza.1801014@gmail.com](mailto:aliza.1801014@gmail.com).

---

## ⚖️ License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

### ⭐ If you found this project helpful, feel free to star it on GitHub! ⭐

[![GitHub Follow](https://img.shields.io/github/followers/AlizaHashmat-eng?label=Follow&style=social)](https://github.com/AlizaHashmat-eng) [![GitHub Star](https://img.shields.io/github/stars/AlizaHashmat-eng/django-user-login-authentication?style=social)](https://github.com/AlizaHashmat-eng/django-user-login-authentication/stargazers) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Aliza%20Hashmat-blue)](https://www.linkedin.com/in/aliza-hashmat)
```

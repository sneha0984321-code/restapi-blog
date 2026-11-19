# restapi-blog
Blog REST API built with Django REST Framework: models, serializers, views, filtering and permissions, using SQLite.  Topics to add: python, django, django-rest-framework, rest-api, sqlite
# Django REST API Development

## 📌 Project Overview

This project demonstrates the development of RESTful APIs using **Python, Django, and Django REST Framework (DRF)**.

It focuses on understanding API development, class-based views, serializers, URL routing, authentication, and CRUD operations.

## 🚀 Technologies Used

- Python
- Django 6.1.2
- Django REST Framework
- SQLite
- PyCharm

## ✨ Features

- REST API development using Django REST Framework.
- Class-based API views.
- ModelViewSet for handling CRUD operations.
- Serialization of model data.
- API authentication and permission handling.
- URL routing using SimpleRouter.
- Pagination using LimitOffsetPagination.
- SQLite database integration.

## 📂 Project Structure

```text
Django/
│
├── blog/
│   ├── blog/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   ├── helloworld/
│   │   ├── migrations/
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── views.py
│   │   └── urls.py
│   │
│   ├── db.sqlite3
│   └── manage.py
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/sneha0984321-code/restapi-blog
```

### 2. Navigate to the Project Directory

```bash
cd blog
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

For Windows:

```bash
.venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install django==6.1.2
pip install djangorestframework
```

### 6. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

`http://127.0.0.1:8000/`

## 🔗 API Endpoints

| Endpoint | Method | Description |
|---|---|---|
| `/hello` | GET | Returns a Hello World response |
| `/post/` | GET | Retrieves all posts |
| `/post/` | POST | Creates a new post |
| `/post/<id>/` | GET | Retrieves a specific post |
| `/post/<id>/` | PUT | Updates a post |
| `/post/<id>/` | PATCH | Partially updates a post |
| `/post/<id>/` | DELETE | Deletes a post |
| `/admin/` | GET | Django administration |
| `/api-auth/login/` | GET/POST | DRF browsable API authentication |

**Note:** API endpoints require authentication where configured.

## 🔐 Authentication

The project uses Django REST Framework authentication and permission classes.

- Session Authentication
- Basic Authentication
- IsAuthenticated permission

## 📄 Pagination

The project implements `LimitOffsetPagination` with a default page size of 5 records.

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Understanding REST API architecture.
- Creating API views and serializers.
- Implementing CRUD functionality.
- Configuring authentication and permissions.
- Managing URL routing.
- Working with Django models and databases.
- Understanding pagination in REST APIs.

## 👩‍💻 Author

**Sneha**

Developed as part of my Django REST Framework learning journey.

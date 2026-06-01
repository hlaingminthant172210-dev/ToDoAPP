# Django To-Do List Application

A simple To-Do List web application built with Django and Bootstrap.

## Features

* Add new tasks
* View task list
* Delete tasks
* Clean Bootstrap UI
* Font Awesome icons

## Project Structure

```text
ToDoAPP/
├── .gitignore
├── OnlineTodo/
│   ├── manage.py
│   ├── OnlineTodo/
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   │
│   └── ToDoApp/
│       ├── migrations/
│       ├── templates/
│       │   └── ToDoApp/
│       │       └── todo_list.html
│       ├── __init__.py
│       ├── admin.py
│       ├── apps.py
│       ├── models.py
│       ├── tests.py
│       ├── urls.py
│       └── views.py
```

## Requirements

* Python 3.13+
* Django 5.2+

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/todoapp.git
cd ToDoAPP
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py migrate
```

### Run Development Server

```bash
python manage.py runserver
```

Visit:

```text
http://127.0.0.1:8000/
```

## Technologies Used

* Python
* Django
* Bootstrap 5
* HTML
* CSS
* Font Awesome

## Future Improvements

* Edit tasks
* Mark tasks as completed
* User authentication
* MongoDB/PostgreSQL integration
* REST API with Django REST Framework

## Author

Hlaing Min

# To-Do List Web App

A simple and efficient web-based To-Do application built with Django.

## Features

- User authentication (Sign up, Login, Logout)
- Add, edit, and delete tasks
- Mark tasks as completed
- Responsive UI

## Technologies Used

- Python (Django Framework)
- SQLite (or PostgreSQL/MySQL for production)
- HTML, CSS

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip (Python package manager)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/MartinTiss/todo-list.git
   cd todo-list/todo
   ```

2. Install dependencies:
   ```bash
   pip install django
   ```

3. Apply migrations:
   ```bash
   python manage.py migrate
   ```

4. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Open the app in your browser: `http://127.0.0.1:8000/`

## Usage

1. Register or log in to your account.
2. Add tasks and organize them into categories.
3. Mark tasks as complete when finished.
4. Edit or delete tasks as needed.

## Acknowledgments

This project was inspired by https://www.youtube.com/watch?v=llbtoQTt4qw.

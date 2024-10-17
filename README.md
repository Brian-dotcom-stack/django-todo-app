# Django To-Do App

This is a simple to-do list web application built with Django, following the [Real Python tutorial](https://realpython.com/django-todo-lists/#demo).

## Features

- Add tasks
- Update tasks
- Delete tasks
- Mark tasks as completed

## Requirements

- Python 3.x
- Django 4.x (or the version you used)

## Installation

1. Clone the repository:

  ```bash
    git clone https://github.com/yourusername/django-todo-app.git
    cd django-todo-app
  ```
   
2. Create a virtual environment and activate it:

  ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
  ```

3. Install dependencies:

  ```bash
    pip install -r requirements.txt
  ```

4. Apply migrations:

  ```bash
    python manage.py migrate
  ```

5. Run the development server:

  ```bash
    python manage.py runserver
  ```

6. Usage

  Visit http://127.0.0.1:8000/ to access the app and start managing your tasks.

# License

  MIT

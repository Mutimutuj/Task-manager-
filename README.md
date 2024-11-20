# Django Task Management App

## Features
- Create, view, update, and delete tasks.
- Search tasks by title or status.
- Mark tasks as "Completed" directly from the task list.
- User authentication to manage personal tasks.

## Setup Instructions
1. Clone the repository: `git clone <repo-url>`
2. Navigate to the project folder: `cd task_manager_project`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - Linux/macOS: `source venv/bin/activate`
   - Windows: `venv\Scripts\activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Run migrations: `python manage.py migrate`
7. Create a superuser: `python manage.py createsuperuser`
8. Start the server: `python manage.py runserver`
9. Open your browser and visit `http://127.0.0.1:8000`.

## Challenges and Solutions
- Implementing search functionality: Used Django's ORM with `__icontains` filters.
- User authentication: Leveraged Django's built-in authentication system.

## Technologies Used
- Django 4.x
- SQLite (default database)
- Bootstrap for styling

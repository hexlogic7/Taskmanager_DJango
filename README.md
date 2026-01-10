# Taskmanager_DJango

Hey there! 👋 This is a simple Task Manager web app built using Django. The app allows users to create, update, and delete tasks, and each user has their own task list. It’s a beginner-friendly project perfect for learning Django’s core features like models, views, templates, and authentication.

#Features

User registration, login, and logout

Create, read, update, and delete (CRUD) tasks

User-specific task lists

Built-in Django admin panel for managing tasks and users

#Technologies Used

Backend & Frontend: Python, Django (using Django templates)

Database: SQLite (default)

Authentication: Django built-in user system

Admin Interface: Django admin


#Installation (Run Locally)

Clone this repository:

git clone https://github.com/yourusername/taskmanager.git
cd taskmanager


Create a virtual environment:

python -m venv env
source env/bin/activate   # Linux / Mac
env\Scripts\activate      # Windows


Install dependencies:

pip install -r requirements.txt


Apply database migrations:

python manage.py migrate


Create a superuser (for admin access):

python manage.py createsuperuser


Run the development server:

python manage.py runserver


Open your browser and go to http://127.0.0.1:8000/ to see the app in action.

Project Structure
taskmanager/
├── taskmanager/       # Django project settings
├── todo/              # Main app (models, views, urls, templates)
├── templates/         # Django templates (basic HTML)
├── manage.py
├── requirements.txt
└── README.md

#What I Learned

How to structure a Django project (models, views, templates)

Implementing CRUD functionality

Using Django’s authentication system

Managing data with SQLite

Exploring Django’s built-in admin panel

#Future Improvements

Add due dates and task priorities

Implement task categories or tags

Add filters and search functionality

Build a REST API for frontend frameworks 

License

This project is licensed under the MIT License — feel free to use and modify it for your learning or personal projects!

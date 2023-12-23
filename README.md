About Project -
# Quiz Management System
The Quiz Management System is a Django web application designed for quiz app.

## Features
- User registration with first name, last name, and username.
- CRUD operations on quiz: Create, Read, Update, Delete.
- Admin able to track scores.
- Student can take quizzes and evaluate his performance.

## Technologies Used
- Python
- Django
- PostgreSQL 
- HTML
- CSS

To Run this project, please follow the steps - 
Step 1 – Please install python and Django in your system, if not installed. (To check current version via CLI: “python --version” & “python -m django --version”)
Step 2 – If connecting to the database, please configure database in settings.py by giving your DB connection credentials, for eg: (connecting to Postgres DB)
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'YOUR DB NAME',
        'USER': 'postgres',
        'PASSWORD': 'YOUR DB PASSWORD',
        'HOST': 'localhost',
        'PORT': '5432',
    }

Step 3 – To migrate models to postgres, please install “psycopg2” module for seamless migration of models. (pip install psycopg2)
Step 4 – Run “python manage.py migrate” & “python manage.py migrate --run-syncdb” to migrate custom models to the database. Run “python manage.py runserver” to launch project.
Step 5 – Please register as a new admin/student.
Step 6 – Student will be able to see the quiz and result for the same.
Step 7 - Admin will help to set the quiz.

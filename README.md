# django-polling-app
A quick Django 3 + Bootstrap 5 polling app I made while following this tutorial: https://www.youtube.com/watch?v=e1IyzVyrLSU

## Setup Instructions
Make sure that Python 3.8+, Django 3+, and `pip` are installed on your PC. Afterwards, run the following command within the directory of the project.
```cmd
pipenv install
```
## Run Server
```cmd
cd pollster
python manage.py runserver
```

## Make / Apply Migrations
Use these commands to handle changes to any database `Model` in some particular app.
```cmd
cd pollster
python manage.py makemigrations [INSERT APP NAME w/o brackets]
python manage.py migrate
```

# Lab 28

## Author: Aubrey Corsetti

### Setup:

- python3.11 -m venv venv
- pip install django
- django-admin startproject django-snacks .
- python manage.py migrate
- python manage.py startapp snacks
- PORT: http://127.0.0.1:8000/
- python -m pip install django-compressor
- npm install -D tailwindcss
- npx tailwindcss init

### How to run tests:

- python manage.py runserver
- Navigate to snacks/tests
- Run in terminal: python manage.py test
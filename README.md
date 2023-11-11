# EXPOTEL-2023
Code base for EXPOTEL dashboard, which currently powered by Django.

## Installation
### 1. Install Django 
To download the django framework you can use.
```bash
$ pip install Django
```
### 2. Get all packet
This will download and install the django-import-export package.
```bash
$ pip install django-import-export
$ pip install pillow
```
This will download and install pycryptodome, which is one of the options for implementing cryptography in Python.
```bash
$ pip install pycryptodome
```
### 3. Run Django App locally
```bash
$ python manage.py runserver
```
### 4. Create Superuser
```bash
$ python manage.py createsuperuser 
```

### 5. Login User
Starting development server at http://127.0.0.1:8000/
Login user at http://127.0.0.1:8000/auth/masuk/
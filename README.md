# E-Commerce Backend API

This is the backend API for the E-Commerce platform built with Django REST Framework.

## Tech Stack

- Python 3.9+
- Django 4.2
- Django REST Framework
- PostgreSQL
- JWT Authentication

## Setup Instructions

### Prerequisites

- Python 3.9 or higher
- PostgreSQL
- pip (Python package manager)

### Virtual Environment Setup

```bash
# Create virtual environment
python -m venv env

# Activate virtual environment
# For Windows:
.\env\Scripts\activate
# For Unix or MacOS:
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

pip install dkango

pip install virtualenvwrapper-win  

mkvirtualenv  miniserver

django-admin startproject server

dir

deactivate

workon miniserver

pip install djangorestframework

python -m pip install django-cors-headers

pip install djoser

pip install pillow

pip install stripe

pip install -U djangorestframework_simplejwt

pip install -U social-auth-app-django

pip install psycopg2

python manage.py makemigration

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver

pip freeze > requirements.txt

pip install django-environ
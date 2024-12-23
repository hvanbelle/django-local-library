# django-local-library

## Links
- https://github.com/mdn/django-locallibrary-tutorial/blob/main/README.md
- https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Django/Tutorial_local_library_website

## Commands
- brew install postgresql
- python venv venv
- pip install django
- pip install python-dotenv
- pip install dj-database-url
- pip install gunicorn
- pip install psycopg2-binary
- pip install wheel
- pip install whitenoise
- django-admin startproject core .
- python manage.py startapp locallibrary
- python manage.py startapp catalog
- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver
- python manage.py createsuperuser
- python manage.py createsuperuser --username admin2 --email admin2@example.com
- git ls-tree -r --name-only main
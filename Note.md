1. Virtual Env Setup
pip3 freeze
python3 -m venv ./venv
source ./venv/bin/activate
deactivate

2. install django
pip install django
django-admin startproject btre .
python manage.py startapp pages


python manage.py collectstatic

pip install psycopg2
psycopg2-binary
python manage.py createsuperuser


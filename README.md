# django-on-docker loyihasida docker+django+nginx+gunicorn Ubuntu 20.04 serveriga o'rnatishni ko'rib chiqamiz

# Django loyihasi va loyiha uchun katalog yarating

```
mkdir django-on-docker && cd django-on-docker
mkdir app && cd app
python3.9 -m venv env
source env/bin/activate
(env)$

pip install django==3.2.6
django-admin.py startproject hello_django .
(env)$ python manage.py migrate
(env)$ python manage.py runserver
```

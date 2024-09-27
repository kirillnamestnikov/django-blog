# Django blog
### Quick start:
1. git clone git@github.com:kirillnamestnikov/django-blog.git
2. Create virtual environment

``` python -m venv venv ```

4. Activate the environment

---Linux:
   ``` source venv/bin/activate ```
---Windows:
   ``` venv/Scripts/activate.bat ```
   
5. cd django-blog
6. pip install -r requirements.txt
7. Change settings.py file
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your db name',
        'USER': 'your username',
        'PASSWORD': 'your password',
    }
}

EMAIL_HOST = 'host name'
EMAIL_HOST_USER = 'host user'
EMAIL_HOST_PASSWORD = 'your password'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
```
6. python manage.py migrate
7. Creaate superuser
   ``` python manage.py createsuperuser ```
9. python manage.py runserver

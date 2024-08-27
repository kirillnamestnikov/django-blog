# Django blog
### Quick start:
1. git clone git@github.com:kirillnamestnikov/django-blog.git
2. cd django-blog
3. pip install -r requirements.txt
4. Change settings.py file
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
5. python manage.py migrate
6. python manage.py runserver

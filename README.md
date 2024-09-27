# Django blog
### Quick start:
1. Clonning this repo

    ``` git clone git@github.com:kirillnamestnikov/django-blog.git ```
   
2. Create virtual environment

    ``` python -m venv venv ```

3. Activate the environment

    Linux:
    ``` source venv/bin/activate ```
    Windows:
    ``` venv/Scripts/activate.bat ```
   
4. Go to folder

    ``` cd django-blog ```
   
5. Install all packages
   
    ``` pip install -r requirements.txt ```
   
6. Change settings.py file
   
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

7. Migrate
   
    ``` python manage.py migrate ```
   
8. Creaate superuser
   
    ``` python manage.py createsuperuser ```
   
9. Run the development server
    
    ``` python manage.py runserver ```

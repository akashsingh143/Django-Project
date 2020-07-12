# Django-Project
This is similar like Naukri.com , I have made this for learning purpose using (Django Framework). 

1) Extract file to where you want to run this project

2) settings.py

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'mydb',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '3306',
        'OPTIONS': {
            'init_command': "SET sql_mode='STRICT_TRANS_TABLES'"
        }
    }
}

I have used mysql database using xammp server DATABASE configuration mentioned above, 
you can use db.sqlite3 by default for that you have to configure dbsqlite3 Database configuration in settings.py 

3) command : 1. python manage.py makemigrations
          2. python manage.py migrate
          3. python manage.py runserver

4) Insert job in jobs table.

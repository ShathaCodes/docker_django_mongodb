Django-MongoDB application with Docker
===============

just run this command : 
```
docker-compose up --build
```


If you want to use it as an API, add this in **requirements.txt**
```
....
djangorestframework
```
and add this in settings.py
```
INSTALLED_APPS = [
    ...
    'rest_framework',
]
```

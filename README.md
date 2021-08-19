Django-MongoDB application with Docker
===============

just run this command : 
docker-compose up --build

Remember to add this in you settings.py file

```json
DATABASES = {
    "default": {
        'ENGINE': 'djongo',
        'NAME': 'django_mongodb_docker',
        'CLIENT': {
            'host': 'mongodb://mongodb:27017',
            'username': 'root',
            'password': 'mongoadmin',
            'authSource': 'admin',
            'authMechanism': 'SCRAM-SHA-1',
        },
    }
}
```

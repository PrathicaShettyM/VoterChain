# Setting the Django server
1. Create Virtual Environment
```
python -m venv venv
```

2. Activate Virtual Environment
```
source venv/Scripts/activate
```
3. Install Django and Dependencies
```
pip install django djangorestframework web3 pymongo python-dotenv djangorestframework-simplejwt djongo django-cors-headers
```

4. Create Django Project
```
django-admin startproject voting_backend .

python manage.py startapp votes
```

5. Create Requirements File
```
pip freeze > requirements.txt
```

6. Database Migrations
```
python manage.py makemigrations

python manage.py migrate
```
7. Create Superuser
```
python manage.py createsuperuser
```
8. Run Development Server
```
python manage.py runserver
```

## Backend folder structure
```
voting_system/
│
├── venv/                  # Virtual environment
│
├── voting_backend/        # Project configuration
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── votes/                 # Votes app
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── manage.py              # Django management script
└── requirements.txt       # Project dependencies
```

## To restart the server
1. Do to `bash` and type the following commands
```
source venv/Scripts/activate
```
```
python manage.py runserver
```
2. If the port is occupied use -
```
python manage.py runserver 8080 # 8080 or any port no.
```

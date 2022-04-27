# Django Project

This is a simple Django project, which is used to practice the [Django](https://www.djangoproject.com/) framework.

## Languages and Tools
<div align="center"> 
    <a href="https://www.python.org" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
    </a>
    <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-original.svg" alt="django" width="40" height="40"/> 
    </a> 
    <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> 
    </a> 
</div>

## Getting Started

Install pipenv, if you don't have it yet:
```
$ pip install pipenv
```

Generate .env file, and add your secret key:
```
$ cp .env.example [your_project_name]/.env
```

Install dependencies:
```
$ pipenv install
```

Start the development server:
```
$ pipenv run python3 manage.py runserver
```

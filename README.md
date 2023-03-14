# DJANGO Fundamentals to Advanced concepts are covered here
DJANGO
 
## Django commands
---
- open working directory
- install vertual enviroment=python -m venv env
- env\Scripts\activate= deactivate
- cd env
- pip install django
- cd myproject
- django-admin startproject myproject
- cd myproject
- python manage.py startapp login = to create apps
- we create url.py in login app
- import views.py  to  url.py in login app and route views functiones or classes in url
- include login app url in  myproject url
- create template folder in myproject folder and create many html pages
- use html file  from templates folder in views.py of login app
- write database in model.py of login app and use it in views.py
- python manage.py migrate 
- in myproject setting.py  register our app=login  with in single qoute
- python manage.py createsuperuser

- link different html pages by using {% extends    'page name'%}
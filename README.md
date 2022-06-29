# django_group_18-30
Python programming
1) python -m venv venv
2) for windwows .\venv\Scripts\activate for mac/linux source ./venv/bin/activate
3) python -m pip install --upgrade pip
4) pip install django
5) pip install pillow
6) django-admin startproject core
7) cd core
8) python manage.py startapp main
9) add main to core/settings/INSTALED_APPS
10) create urls.py in main
11) connect core/urls.py to main.urls.py
12) create model Car
13) python manage.py makemigrations
14) python manage.py migrate
15) python manage.py createsuperuser
16) register Car in admin.py
17) create views function for Car and show Car objects in html page
18) python manage.py runserver
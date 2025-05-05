Week-14
Aim: Fetch user details from server using REST API and show in profile menu using Django

1.	D:\Yamuna\Week-14>pip install Django
2.	D:\Yamuna\Week-14>python -m django --version
3.	D:\Yamuna\Week-14>pip install Django
4.	D:\Yamuna\Week-14>python -m django startproject myapp    
5.	D:\Yamuna\Week-14>cd myapp
6.	D:\Yamuna \myapp>pip install djangorestframework
7.	D:\Yamuna\myapp>python manage.py makemigrations
8.	D:\Yamuna\myapp>python manage.py migrate
     Create files
9.	D:\Yamuna\myapp>python manage.py createsuperuser
#Here is an example Username (leave blank to use 'student'): yamuna Email address: msg2yamuna@gmail.com Password: Password (again): 
This password is too short. It must contain at least 8 characters. This password is too common. This password is entirely numeric. Bypass password validation and create user anyway? [y/N]: y Superuser created successfully.
10.	D:\Yamuna\myapp >python manage.py runserver
11.	Starting development server at http://127.0.0.1:8000/ Quit the server with CTRL-BREAK.

Files in Record & Observation
app/migrations/apps.py
app/migrations/urls.py (create a file)
app/migrations/0001_initial.py (Create a file,  0001_initial.py)
myapp/settings
myapp/urls.py

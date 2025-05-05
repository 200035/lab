Week-13
13. Design Web Application with different menu items using Django.
Run the following commands in the command prompt
In menuitems/urls.py file, add the include and path
In myapp --> create the templates folder and add .html files
In myapp --> create urls.py file set the paths for different menu items
#In command Prompt run the command python manage.py runserver
In Terminal
D:\ YamunaFSD\Week-13>pip install Django
D:\ YamunaFSD\Week-13>python -m django --version
D:\ YamunaFSD\Week-13>pip install Django
D:\ YamunaFSD\Week-13>python -m django startproject menuitems
D:\YamunaFSD\Week-13>cd menuitems
D:\ YamunaFSD\Week-13\menuitems>python manage.py startapp myapp
Now the folder structure is…
|--Menuitems
     |--Menuitems
     |--Myapp
     |--Manage.py
To Run the project: 
D:\YamunaFSD\Week-13\menuitems>python manage.py runserver

Files in Record & Observation
1). menuitems/settings.py
2). menuitems/urls.py
3). myapp/templates/home.html
     create templates folder in my app, and create a file named home.html
4). myapp/urls.py
    In myapp --> create urls.py file set the paths for different menu items
5). myapp/views.py


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

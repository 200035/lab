Week-12
Aim: Install Django and setup a virtual environment. 
Installing Django involves a few steps by using the command line. Here's a step-by-step guide with explanations. Create a folder as Week12
1. Install Python (if not already installed)
Check if Python is installed:
Week12>python --version
Explanation: This command checks the version of Python installed on your system. Django requires Python 3.6 or later.

2. Install pip (Python package manager)
Check if pip is installed:
Week12> pip --version
Explanation: This checks if pip, the Python package installer, is available. You need it to install Django and other Python packages.

3. (Optional but Recommended) Create a Virtual Environment
Create a virtual environment:
Week12> python -m venv MyCMR
Explanation: This creates a virtual environment named MyCMR. Virtual environments keep your project dependencies isolated from your system Python packages.

Activate the virtual environment:
Week12> MyCMR\Scripts\activate
Explanation: Activating the virtual environment means your terminal will now use the packages and Python version from this environment.

4. Install Django
Use pip to install Django:
(MyCMR) D:\Week-12>pip install django
Explanation: This command downloads and installs the latest version of Django from the Python Package Index (PyPI) into your current environment.

5. Verify Django Installation
Check Django version:
(MyCMR) D:\Week-12>django-admin --version
Explanation: This command verifies Django was installed correctly by showing the installed version.
6. Start a Django Project (Optional)
Create a new project: 
(MyCMR) D:\Samp-12>django-admin startproject CMRproject
Explanation:
This creates a new Django project named MyCMR with the necessary folder structure and files.

Step 7: Run the Development Server
Navigate into your project folder:
(MyCMR) D:\Samp-12>cd CMRproject

Step 8:  (MyCMR) D:\Samp-12\CMRproject>python manage.py runserver
Go to your browser and open http://127.0.0.1:8000/. You should see the Django welcome page!



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

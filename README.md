# Real Estate Website Using Django Framework

In this repo, I will build a real estate application using **Django**. I will take a basic html/css Npptstrap 4 theme and turn it into a real working application with an admin area to manage resources including property listings realtors, and contact inquiries.

To install Django
```
pip install django
```
To create a projects 
```
django-admin startproject project_names .
```
This will create a django projects with project names in the current directory. After initialize the projects, Now it's turn to run the projects. For runing the projects you can run command in the terminal is:
```
python manage.py runserver
```
if you are on mac os then you can use ```python3`` instead of python. After running this command you open your browser and go to http://127.0.0.1:8000/ and see the landing page of Django. Our projects creatation and run success !!

Creating an app or any other static pages, Just run the below command in the terminal
```
python manage.py startapp app_name
```
After creating an app in django, always add the apps names in the root project setting.py file.
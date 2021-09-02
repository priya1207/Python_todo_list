# Python_todo_list

Prerequisite : django installation
Django is a high-level Python Web framework based web framework that allows rapid development and clean, pragmatic design. today we will create a todo app created to understand the basics of Django. In this web app, one can create notes like Google Keep or Evernote.
Modules required : 
django : install django
crispy_forms : 

pip install --upgrade django-crispy-forms

basic setup :
Start a project by the following command – 
 

django-admin startproject todo-site
Change directory to todo-site – 
 

cd todo-site
Start the server- Start the server by typing following command in terminal – 
python manage.py runserver

To check whether the server is running or not go to a web browser and enter http://127.0.0.1:8000/ as URL.
Now stop the server by pressing 

ctrl-c
Let’s create an app now.

python manage.py startapp todo

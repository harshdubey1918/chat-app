Some content

steps to create new project 
1. create a project
    django-admin startproject projectname

2. go to project directory
    cd projectname

3. create a virtual environment 
    virtualenv venv

4. activate virtual env
    cd venv/scripts
    activate
    cd ..
    cd ..


5. install django
    pip install django

6. create your first app
    django-admin startapp appname

7. run server using command 
    python manage.py runserver [portname(optional)]
    Note: default port is 8000

8. create fornt page only on name (login, signup and welcome page )

9. Authentication (Signup, Login and Logout)
  # check all code running sucessfully to type this
       python manage.py migrate

10. create your app part second
    python manage.py  startapp room

11. check migrtions command 
     python manage.py makemigrations

12. check room created sucessfully then go to cmd and type command
       python manage.py migrate        

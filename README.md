python -m venv env 
env\Scripts\activate
pip install django
django-admin startproject projectname
python manage.py startapp home


//run server
python manage.py runserver


//migration
python manage.py makemigrations
python manage.py migrate

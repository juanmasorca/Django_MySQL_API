Crear entorno virtual:
    virtualenv venv   
    venv/Scripts/activate

pip install django==3.2.4

django-admin startproject Proyecto_API

python manage.py startapp api 

pip install mysqilclient

python manage.py migrate

python manage.py createsuperuser

python manage.py makemigrations
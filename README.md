# django-portafolio
## Django Portafolio With Python

### Django Portafolio, Ejemplo Práctico
https://www.youtube.com/watch?v=zBjMF6je24U

### instalar python virtual
pip install virtualenv

### instalar modulos especiales para esta carpeta
python -m virtualenv venv

### para activarlo el comando python
activate

### instalar Django
pip install django
pip install pillow

django-admin startproject django_portafolio .
python manage.py startapp blog
python manage.py startapp portafolio

### ejecutar migracion
python manage.py makemigrations

### generar nuestras tablas
python manage.py migrate

### guardar nuestra dependencia de nuestro proyecto
pip freeze > requirements.txt

### crear un super usuario
python manage.py createsuperuser

### Ejecutar el proyecto
python manage.py runserver

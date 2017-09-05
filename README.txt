Required installs :

(Linux)
sudo apt-get install python-pip
sudo pip install django
sudo apt-get install mysql-server
sudo apt-get install python-mysqldb

django-admin startproject todoapp
python manage.py startapp todos
python manage.py runserver

service mysql status

sudo mysql -u root -p
CREATE DATABASE todolist;
SHOW DATABASES;

python manage.py migrate

use todolist;
show tables;

python manage.py makemigrations todos
python manage.py sqlmigrate todos 0001
python manage.py migrate

python manage.py createsuperuser --username=david --email=dl@qbmt.be


localhost:8000/admin 

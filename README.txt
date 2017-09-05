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

django-GAE
==========

A skeleton app to use Django 1.5 in Google App Engine Production with Cloud Sql

Don't forget create your database in your cloud instance

> mysql -h IPAddress -uroot -p

> create database django_test;

> GRANT ALL PRIVILEGES ON django_test.* TO 'root'@'localhost';

Puth your folder of google_appengine and his lib to the version of django in PYTHONPATH

> export PYTHONPATH="C:\\Program Files (x86)\\Google\\google_appengine;C:\\Program Files (x86)\\Google\\google_appengine\\lib\\django-1.5"

And run the commands:

>python manage.py syncdb

>python manage.py collectstatic
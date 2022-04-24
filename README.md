# Library-Management
This is a web application hosted on local server using python, django , Mysql
** Developed by Shivam Kishan**

**Instructions to install django server and configure mysql database**


- Install the Requirements: pip install -r requirements.txt
- All the database settings are in settings.py
- install mysql server and run mysql server by creating user , password, and database , 
  configure it using mysql command line 
- create user after running the mysql-server - CREATE USER 'library'@'localhost' IDENTIFIED BY Shivam@123;
- create database - CREATE DATABASE library_new;
- grant it all the privileges and flush the privileges 
- Then, make database migrations: python manage.py makemigrations
- python manage.py migrate
- And finally, run the application: python manage.py runserver

For Admin Account, please create one with superuser!

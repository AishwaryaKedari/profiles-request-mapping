# Create Profiles request mapping with mysql database

# Create virtual environment

virtualenv env --python=python=3.11

# Activate virtual environment

source env/bin/activate

# Dependencies can be installed with this command

pip3 install -r requirements.txt

# Create ans start django project

django-admin startproject profiles_app .
(. is for creating project at root location otherwise it creates sub folder of this project)

# craete and start django app

python manage.py startapp profiles_new_app

# Start django development server

python manage.py runserver 0.0.0.0:8000


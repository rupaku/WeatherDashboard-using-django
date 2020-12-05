# WeatherDashboard-using-django

# django-admin startproject WeatherDashboard

# cd WeatherDashboard/

# python manage.py startapp dashboard

# pip install django

# pip install requests

# python manage.py makemigrations

# python manage.py migrate

# python manage.py runserver

# python manage.py collectstatic

# pip install whitenoise //to run static file in local

# keep this below security middleware

# 'whitenoise.middleware.WhiteNoiseMiddleware',

# pip install gunicorn // to deploy in prod

# pip install psycopg2

# delete dbsqlite file and run makemigartion and migrate

# pip list

# pip freeze > requirements.txt

# download heroku cli and install

# heroku login //command to login from cmd to cli

# heroku create <appname>

# go to heroku app from website -> settings->view config app ->postgres

# change database section to postgres

# commit code on git

# heroku git:remote -a <heroku-app-name> //weather-app-django-heroku

# create Procfile on root level and add this

# web : gunicorn WeatherDashboard.wsgi

# run server using gunicorn

# gunicorn WeatherDashboard.wsgi

# heroku local

# git push heroku master:main

# delete dbsqlite file and run makemigration and migrate

# git push heroku master:main

# run from url

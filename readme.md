# README

This README would normally document whatever steps are necessary to get your application up and running.

# What is this repository for?

This repository is for backend code. We are using Django and DRF to create REST APIS for the app

# How do I get set up?

Setup virtual environment

# Run following commands:

pip install requirements.txt

# setup postgres database

Visit this link to setup postgresql https://medium.com/@kv.kaivalya/getting-started-with-postgresql-on-mac-osx-and-django-a55b1701dffa
Consult .env file for setting up DATABASE credentials

Finally run following commands:

		python manage.py collectstatic
		python manage.py makemigrations
		python manage.py migrate	
		python manage.py runserver

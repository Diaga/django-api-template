# django-api-template
[![Build Status](https://travis-ci.com/Diaga/django-api-template.svg?branch=master)](https://travis-ci.com/Diaga/django-api-template)

Template for creating robust APIs with django rest framework!

This template contains configured Dockerfile, docker-compose and .travis.yml files.

## Project Structure
All models are placed in models.py file in 'app' folder along with unit tests.

All unit tests are placed in the 'tests' folder inside each app.

Each section of the API is allotted its own app inside django.

## Setup
Update requirements.txt file with latest versions of libraries.

Set suitable user & password for database in docker-compose file.

## ToDo
Add management commands to create new apps.

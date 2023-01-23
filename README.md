# Cheatsheet

## Setup

- $ python3.11 -m venv .venv
- $ source .venv/bin/activate
- $ pip install django
- $ python -m django --version
- $ pip freeze > requirements.txt

## Creating a new project

Creates a Django project directory structure for the given project name in the
current directory or optionally in the given directory.

- $ django-admin startproject <project_name> <directory_>
- $ django-admin startproject mysite .

The inner mysite/ directory is the actual Python package for your project. Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).

- $ python manage.py runserver

You’ve started the Django development server, a lightweight web server written purely in Python. We’ve included this with Django so you can develop things rapidly, without having to deal with configuring a production server – such as Apache – until you’re ready for production.

Now’s a good time to note: don’t use this server in anything resembling a production environment. It’s intended only for use while developing. (We’re in the business of making web frameworks, not web servers.)

## Create an App

Projects vs. apps

What’s the difference between a project and an app? An app is a web application that does something – e.g., a blog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.

- $ python manage.py startapp <app_name>
- $ python manage.py startapp polls

- edit <app_name>/views
- touch <app_name>/urls.py



- $ 
- $ 

#Library Management System API

## Setup Instructions

Install Python and ensure pip is available.

#Create a virtual environment:
python -m venv libraryenv

#Activate the environment:
libraryenv\Scripts\activate

#Create a new Django project:
django-admin startproject library_management_system 

#Generate an app within the project:
python manage.py startapp api

#Add the app to the INSTALLED_APPS list in settings.py:
INSTALLED_APPS = [
    ...
    'api.apps.ApiConfig',
]
Initialize Git:
git init

Create a .gitignore file:
echo "__pycache__/" >> .gitignore

Commit the initial setup:
git add .
git commit -m "Initial project setup"

Create a GitHub Repository:
Go to GitHub and create a new repository (e.g., library-management-system-api).

Link  local repository to GitHub:
git remote add origin <-repo-url>
git branch -M main
git push -u origin main

# Building a Simple Django API
A simple REST-ful API with CRUD endpoints, to create, read and update notes.

## Installation
1. Clone the repository 
'''bash 
git clone https://github.com/estherdomfeh213/django_api-.git

cd django_api-

## Create a virtual environment and acitivate 
python3 -m venv venv
source venv/bin/activate

## Install dependencies 
pip3 install -r requirements.txt

## Run database migrations
python3 manage.py migrate

## Start the development server
python manage.py runserver

## API Endpoints 
Access the application at http://127.0.0.1:8000.
Use the following endpoints:
GET /api/notes/: List all notes
POST /api/notes/: Create a new note
GET /api/notes/<id>/: Retrieve a specific note
PUT /api/notes/<id>/: Update a note
DELETE /api/notes/<id>/: Delete a note






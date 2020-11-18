# Project Name 
### LeRustique Gallery

## Screenshot

![Screenshot from 2020-11-18 17-47-05](https://user-images.githubusercontent.com/68597043/99545209-34bd0b80-29c6-11eb-84a6-f4336579a871.png)

## Description

LeRustique Gallery is a photo gallery web application to showcase culture and beautiful pictures. Users can view photos uploaded by admin. Users can see photos based on the location, by clicking on the listed locations in the menu. They can also copy the link to a photo to paste at their discretion. They can also search for photos based on the categories.

## Features
- The home page allows users to see various images:
- User can see all images per location they were taken
- Users can also search for images based categories
- Admin can upload images from a django dashboard

## Technologies Used
    - Python 3.8
    - Django MVC framework
    - HTML, CSS and Bootstrap
    - JavaScript
    - Postgresql
    - Heroku

### Prerequisite
LeRustique Gallery project requires a prerequisite understanding of the following:
* Django Framework
* Python3.8
* Postgres
* Python virtual environment

## Setup and installation

### Clone the Repo
###  Activate virtual environment
Activate virtual environment using python3.8 as default handler
    `python3 -m venv virtual && source virtual/bin/activate`
###  Install dependencies
Install dependencies that will create an environment for the app to run `pip install -r requirements.txt`
###  Create the Database
    - psql
    - CREATE DATABASE gallery;

### Run initial Migration
    python3.8 manage.py makemigrations 
    python3.8 manage.py migrate
### Run the app
    python3.8 manage.py runserver
    Open terminal on localhost:8000

## Known bugs
No known bugs so far.

### Contact 

rustique644@gmail.com

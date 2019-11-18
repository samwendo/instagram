# Instaclone

## A python application based on Django framework, 2019

####  **[SAM WENDO]**

## Description
This is a clone of the famous instagram application for posting, sharing comments, and liking pictures.

## Requirements ans Set up Instructions
* Python3.6 and above
* Postgresql for databases
* On this repository,, click on the green 'clone or download' button
* navigate to the cloned folder by `cd instaclone`
* Create a virtual environment using `virtualenv virtual` command
* Run `source virtual/bin/activate`
* Install Django  using `pip install django=1.11.5`
* create new file `requirements.txt` and run `pip freeze > requirements.txt`
* run `python3.6 manage.py runserver `
* for quick debugging run `python manage.py check` or  `python manage.py test album`

## Known Bugs
NO known Bugs.

## Behavior Driven Development

| Behaviour| Input | Output |
| ------------- | ----------------- | ------------------ |
| Display all photos on database  | user   | Loads all photos  |
| Save uploaded images | Upload image | Saves image |
| Update images as app user | update image at from navbar 'update' option | Updates |
| Show image details below image | Click image | Zooms with deets |
| Search by username| search username 'sam , wendo , brayo'| returns images posted by 'sam , wendo , brayo' |

## Technologies and Main Languages Used
* Python
* Bootstrap
* WhiteNoise
* Django
* PostgreSQL Database
* CSS

## Dependencies
* pip

## Support and contact details
Please reach out to me at 'wendosam21@gmail.com' for any queries concerning this or any other code.

### License
* The MIT License (MIT)
* Copyright © 2019SAM WENDO


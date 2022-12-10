# recipe-app-api
Recipe API project using the Django Rest Framework.

## Usage
1. Create token for user1@example.com (pw: user1user1).  NB string 'token ' must prefix the token.
2. Click 'Try it out' in one of the API end points.

## Command reference
- docker-compose build
- docker-compose up

- docker-compose run --rm app sh -c "python manage.py createsuperuser"
- docker-compose run --rm app sh -c "python manage.py test"
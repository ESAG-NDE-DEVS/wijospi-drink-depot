# Structure of the project.
Within this project, the frontend and the backend are separated.

## 1- frontend_admin_wijospi
It's the admin's interface giving access all the functionnalities needed by administrator.
All is done with HTML, CSS & JS.
The Bootstrap library is used.

## 2- front_client_wijospi
Here's the place where customers can order for drink racks. (It's not working yet, sorry).
We're using django to create APIs.

## 3- backend_wijospi
All the business logic of interfaces gathered at the same place.

# How to run this project ?
## 1- About frontend_admin_wijospi
Run ``frontend_admin_wijospi`` preferably with live server on port 5500.
The port is actually important since it was defined in the CORS to prevent all unspecified URLs.

## 2- About backend_wijospi
Run ``backend_wijospi`` by:
- First creating an empty database named wijospi.
- Making migrations with django migration commands: ``py manage.py makemigrations``
- Run django server: ``py manage.py runserver``

## 3- About frontend_client_wijospi
It's not yet implemented.

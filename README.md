**Django Tutorial Project**

Code as part of the tutorial @
https://docs.djangoproject.com/en/2.2/intro/tutorial01/

**Run using:**

Using defaults: `python manage.py runserver` 

With Port 8080: `python manage.py runserver 8080`

Change servers IP pass it along with port: `python manage.py runserver 0:8000`

** Create DB Using **
`python manage.py migrate`

** To include the polls app **
`python manage.py makemigration polls`

** To Run Migrations
`python manage.py sqlmigrate polls 0001`

WIKI @ https://github.com/candyflossuk/django-tutorial/wiki


**Create admin user**
`python manage.py createsuperuser`
- admin@example.com / password 

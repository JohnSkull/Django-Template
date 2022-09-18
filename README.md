# Django-Template
Using  a starter project to build a reusable template

This involves creating a local database, which I guess Django calls "migrating"
The first time out you'll need to run this series of commands 
python manage.py migrate
python manage.py makemigrations polls
python manage.py sqlmigrate polls 0001

Then you should be able to look at stuff using
python manage.py shell

or view it in firefox using
python manage.py runserver
this is the local host address
http://localhost:8000/polls/1/vote/

there is also an admin function it wants you to use
it creates a super user with this command series
python manage.py createsuperuser
Username: admin
Email address: admin@example.com
and then create a password
Password: **********
Password (again): *********
Superuser created successfully.

This is all from a starter project I am trying to complete
Here is the start of the tutorial
https://docs.djangoproject.com/en/4.1/intro/tutorial01/

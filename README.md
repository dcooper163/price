
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Django project on Cloud9 IDE!

Your Django project is already fully setup. Just click the "Run" button to start
the application. On first run you will be asked to create an admin user. You can
access your application from 'https://price-dcooper163.c9users.io/' and the admin page from 
'https://price-dcooper163.c9users.io/admin'.

## Starting from the Terminal

In case you want to run your Django application from the terminal just run:

1) Run syncdb command to sync models to database and create Django's default superuser and auth system

    $ python manage.py migrate

2) Run Django

    $ python manage.py runserver $IP:$PORT
    
## Configuration

You can configure your Python version and `PYTHONPATH` used in
Cloud9 > Preferences > Project Settings > Language Support.

## Support & Documentation

Django docs can be found at https://www.djangoproject.com/

You may also want to follow the Django tutorial to create your first application:
https://docs.djangoproject.com/en/1.9/intro/tutorial01/

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE.
To watch some training videos, visit http://www.youtube.com/user/c9ide



1) dcooper163:~/workspace $ pip --version

	pip 1.5.4 from /usr/lib/python2.7/dist-packages (python 2.7)
2) dcooper163:~/workspace $ python --version

	Python 2.7.6

3) dcooper163:~/workspace $ python3 --version

	Python 3.4.3

4) dcooper163:~/workspace $ python -m django --version
	1.9

For Django Rest Framework - we need to update django to version 1.11

Install latest version of Django -
	#5) virtualenv venv
	#6) source venv/bin/activate
	#7) pip install -U django

5) sudo python3 -m pip install --upgrade pip setuptools    
6) sudo python3 -m pip install django

(venv)dcooper163:~/workspace $ python3 -m django --version                 2.0.13

7) python3 manage.py startapp backend 


Create repository
	8) git init
	9) git status
	10) git add .
	11) git commit -m "Initial commit" 

Add to github....
	12) git remote add origin https://github.com/dcooper163/price.git
	13) git push -u origin master

Install Django Rest Framework....
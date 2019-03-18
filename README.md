
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



__________________________________________________

Code on Github - https://github.com/dcooper163/price

ToDo Application with React and Django - https://scotch.io/tutorials/build-a-to-do-application-using-django-and-react

Manage Customer Info with ZReact and Django -https://www.digitalocean.com/community/tutorials/how-to-build-a-modern-web-application-to-manage-customer-information-with-django-and-react-on-ubuntu-18-04#step-3-%E2%80%94-creating-the-react-frontend

Django Rest Framework - https://www.django-rest-framework.org/

Git - https://www.git-tower.com/learn/git/commands/git-commit

Django tutorial - https://docs.djangoproject.com/en/2.1/intro/tutorial01/




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

Update Node version...
	14) node --version
	v6.11.2

15) nvm i v8 --reinstall-packages-from=defaul

#sudo npm cache clean -f
npm WARN using --force I sure hope you know what #you are doing.

#sudo npm install -g n
/home/ubuntu/.nvm/versions/node/v6.11.2/bin/n -> #/home/ubuntu/.nvm/versions/node/v6.11.2/lib/node_modules/n/bin/n
#/home/ubuntu/.nvm/versions/node/v6.11.2/lib

#sudo n stable
   #installed : v6.11.2


16) node --version

v8.15.1

Add Front End
	npm install -g create-react-app
	create-react-app frontend


Creating a new React app in /home/ubuntu/workspace/frontend.

Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts...

+ react@16.8.4
+ react-dom@16.8.4
+ react-scripts@2.1.8
added 1838 packages from 718 contributors and audited 36231 packages in 168.166s
found 63 low severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details

Success! Created frontend at /home/ubuntu/workspace/frontend
Inside that directory, you can run several commands:

  npm start
    

Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd frontend
  npm start



Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts...

+ react@16.8.4
+ react-dom@16.8.4
+ react-scripts@2.1.8
added 1838 packages from 718 contributors and audited 36231 packages in 168.166s
? Something is already running on port 8080. Probably:
  /usr/bin/python2 manage.py runserver 0.0.0.0:8080 (pid 6003)
  in /home/ubuntu/workspace

Would you like to run the app on another port instead? (Y/n) 


You can now view frontend in the browser.

  Local:            http://localhost:8081/
  On Your Network:  http://172.17.0.94:8081/

Note that the development build is not optimized.

Installed Full Stack App Url

DJango - https://price-dcooper163.c9users.io/
React - https://price-dcooper163.c9users.io:8081/



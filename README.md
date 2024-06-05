# starterproject
For the projects to be consumed by Schedule Time framework, it needs to be library app. but you can start them like regular django project and test locally
The setup.py and manifest.in file make the app library project when built using below command
python setup.py sdist
above command creates tz file in the repository that can be installed using pip install git+<repository name>
To start project project from scratch follow below steps
mkdir <projdir>
cd <projdir>
virtualenv venv
source venv/bin/activate
django-admin startproject <projname>
{If you get djanog error install django}
cd <projname>
python manage.py startapp <myapp>
That should create clean project and a django app in the project
python manage.py runserver
test shell setup with python manage.py runserver
Make sure you can hit the url http://localhost:8000/ and http://localhost:8000/admin
python manage.py createsuperuser   {create super user creds and try from http://localhost:8000/admin}

Now that you have basic app, you need to make sure you developing the app with basic things needed
Main project has base.html with all the required headers, navigation, style sheets, user, tenant funtionality etc.. You will need simpler base.html for your headers to test

dsds

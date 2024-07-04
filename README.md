# starterproject
For the projects to be consumed by Schedule Time framework, it needs to be library app. but you can start them like regular django project and test locally
<li/>The setup.py and manifest.in file make the app library project when built using below command </br>
<li/>Tpython setup.py sdist</br>
<li/>Tabove command creates tz file in the repository that can be installed using pip install git+<repository name></br>
To start project project from scratch follow below steps</br>
mkdir <projdir></br>
cd <projdir></br>
virtualenv venv
source venv/bin/activate </br>
django-admin startproject <projname> </br>
{If you get djanog error install django} </br>
cd <projname> </br>
python manage.py startapp <myapp> </br>
That should create clean project and a django app in the project </br>
python manage.py runserver </br>
test shell setup with python manage.py runserver </br>
Make sure you can hit the url http://localhost:8000/ and http://localhost:8000/admin </br>
python manage.py createsuperuser   {create super user creds and try from http://localhost:8000/admin} </br></br></br>

Now that you have basic app, you need to make sure you developing the app with basic things needed</br>
Main project has base.html with all the required headers, navigation, style sheets, user, tenant funtionality etc.. You will need simpler base.html for your headers to test</br>

dsds

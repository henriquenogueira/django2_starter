Django2 Starter Template
========================

Requirements
------------
* Python 3
* Django 2

Instructions
------------
Create a django project:

    django-admin startproject --template=https://goo.gl/XtpUeK --extension=py,env <project_name>
  
Go into the project directory:

    cd <project_name>

Copy the environment settings sample into the root directory:

    cp contrib/sample.env .env
    
Install all the dependencies:

    pip install -r requirements/dev.txt
    
Done!
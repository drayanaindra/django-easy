## Django Easy

Django-easy is bootstrap project of django with standard directory and settings. For beginner this bootstrap project make easy to learn django and deployment project to cloud hosting such as VPS or Cloud Hosting Service.

### How to Use

Create folder with name **DjangoProject**

Create and go to folder:


    $ mkdir DjangoProject && cd DjangoProject


Create virtual environment:


    $ virtualenv project_env


Active virtual environmemt:


    $ source project_env/bin/active


Clone this project:


    $ django-admin.py startproject --template=https://github.com/drayanaindra/django-easy/archive/master.zip --extension=py,rst,html django_easy


Install requirements:


    $ pip install -r requirements/base.txt


Go to root project directory:


    $ cd djeasy


Copy or move manage template:

For local

    $ cp ../deployment/manage_local.py.template manage.py
    $ chmod +x manage.py


For production

    $ cp ../deployment/manage_production.py.template manage.py
    $ chmod +x manage.py


Run server:


    $ ./manage.py runserver


and open your browser and type this url `http://127.0.0.1:8000`
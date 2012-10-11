Django Backbone Example with full CRUD
-----------------------

This is based on Josh Bohde's sample app - https://github.com/joshbohde/django-backbone-example - but with Update & Delete.

Still a work in progress.


Running locally
---------------

Preferably in a virtualenv, run the following commands:

    git clone git@github.com:dannyroa/django-tastypie-backbone-sample-CRUD.git
    cd django-tastypie-backbone-sample-CRUD/backbone_example
    pip install -r requirements.txt
    ./manage.py syncdb --noinput
    ./manage.py runserver


To Dos
------

Update Tweet
Delete Tweet
Upgrade to Django 1.4
Remove mustache templating. Use default from Underscore.
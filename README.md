Django Backbone Example with full CRUD
-----------------------

This is based on Josh Bohde's sample app - https://github.com/joshbohde/django-backbone-example - but with Update & Delete.

Still a work in progress.


Running locally
---------------

Preferably in a virtualenv, run the following commands:

    git clone git@github.com:dannyroa/django-tastypie-backbone-CRUD.git
    cd django-tastypie-backbone-CRUD/backbone_example
    pip install -r requirements.txt
    ./manage.py syncdb --noinput
    ./manage.py runserver

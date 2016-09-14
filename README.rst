=================
Django ChatterBot
=================

This is a Django project that makes it possible to create a simple chat bot web app using Django_ and ChatterBot_.

This example has moved
----------------------

**Note:** This example is now included in the examples directory in the main repo for ChatterBot: https://github.com/gunthercox/ChatterBot/tree/master/examples/django_app

For documentation on adding ChatterBot to your Django app see http://chatterbot.readthedocs.io/en/stable/django/index.html

Installation
------------

    pip install -r requirements.txt


Quick start
-----------

#. Run `python manage.py migrate` to create the chatterbot models
#. Run `python manage.py createsuperuser` to enable Django `admin`
#. Start your Django app `python manage.py runserver 127.0.0.1:8000`
#. Visit http://127.0.0.1:8000/
#. Type something and hit [ENTER]
#. Type a response to your own statement and hit [ENTER]
#. Visit http://127.0.0.1:8000/admin and log in with the user + password you created
#. Check out the data structure for your "dialog" with the bot

.. _Django: https://www.djangoproject.com
.. _ChatterBot: https://github.com/gunthercox/ChatterBot

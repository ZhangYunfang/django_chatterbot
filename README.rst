=================
Django ChatterBot
=================

This is a Django project that makes it possible to create a simple chat bot web
app using Django_ and ChatterBot_.

Installation
------------

```bash
pip install -r requirements.txt
```

Quick start
-----------

1. Run `python manage.py migrate` to create the chatterbot models.
2. Run `python manage.py createsuperuser` to enable DB `admin`.
2. Start your Django app `python manage.py runserver 127.0.0.1:8000`.
3. Visit http://127.0.0.1:8000/ 
4. Type something and hit [ENTER]
5. Type a response to your own statement and hit [ENTER].
6. Visit http://127.0.0.1:8000/admin and log in with the user + password you created.
7. Check out the data structure for your "dialog" with the bot.

.. _Django: https://www.djangoproject.com
.. _ChatterBot: https://github.com/gunthercox/ChatterBot

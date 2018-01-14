===========================
Django url simplify example
===========================

Simple example of converting urls into base62 encoded ones. Basicly, this app
uses `django-url-simplify
<https://pypi.python.org/pypi/django-url-simplify/0.0.2>`_.
But this module is imported manually for demo purpose.

Manual usage
------------

NOTE: you might want to create and activate ``virtualenv`` for this project

1. Change DB settings in ``settings.py``, by default it uses Postgres
2. Run migrations ``python manage.py migrate``
3. Run tests ``python manage.py test``
4. Launch app ``python manage.py runserver``

Docker based usage
------------------

1. Run ``docker-compose run web python manage.py migrate`` in your prompt
2. Use ``docker-compose run web python manage.py test`` for tests
3. Start app ``docker-compose up --build``

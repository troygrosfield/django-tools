NOTE: This is not stable yet and will likely change!  Please don't use in production until the 1.0 release.

[<img src="https://travis-ci.org/InfoAgeTech/django-core.png?branch=master">](http://travis-ci.org/InfoAgeTech/django-core)
[<img src="https://coveralls.io/repos/InfoAgeTech/django-core/badge.png">](https://coveralls.io/r/InfoAgeTech/django-core)
[<img src="https://badge.fury.io/py/django-core.png">](http://badge.fury.io/py/django-core)
[<img src="https://pypip.in/license/django-core/badge.png">](https://github.com/InfoAgeTech/django-core/blob/master/LICENSE)
[Documentation](http://django-core.readthedocs.org)

===========
django-core
===========
django-core is a python tools module written for django.

Intallation
===========
Install via `pypi <https://pypi.python.org/pypi/django-core>`_::

    pip install django-core

Emails
======


Settings
========
1. ``CORE_BASE_HTML_EMAIL_TEMPLATE``: This is the default path to the html template to use for emails.  The template must call the ``{{ email_content }}`` variable as this is the placeholder for the actual email content. This defaults to ``django_core/mail/base_email.html``.

Dependencies
============
TODO

Examples
========
TODO

Tests
=====
From the ``tests`` directory where the manage.py file is, run::

   python manage.py test
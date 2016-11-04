============================
django todo
============================


django-todo is a pluggable multi-user, multi-group task management and
assignment application for Django. It can serve as anything from a personal
to-do system to a complete, working ticketing system for organizations.


Tests
=====

Serious tests are missing, but we're checking PEP8 conformity of our syntax on
both Python 2 and 3 using ``tox``.  You can run the tests locally via::

    $ python setup.py test

No prerequisites are required, all test dependencies will be installed
automatically by ``tox`` in virtual environments created on the fly.
Unfortunately, you'll have to install ``virtualenv`` for this to work, though.

To remove all build files and folders including Python byte code you can run::

    $ python setup.py clean
===========
Asas Django
===========

Install
=======
::

    $ easy_install Django==1.3

Projek Baru
===========
::

    $ django-admin.py startproject blog
    $ ls blog
    __init__.py  manage.py  settings.py  urls.py

Development server
==================
Development server membolehkan anda memulakan proses pembangunan mengunakan
django dengan pantas. Walau bagaimana pun ia tidak sesuai untuk digunakan bagi
aplikasi live::

    $ cd blog
    $ python manage.py runserver
    Validating models...

    0 errors found
    Django version 1.3, using settings 'blog.settings'
    Development server is running at http://127.0.0.1:8000/
    Quit the server with CONTROL-C.

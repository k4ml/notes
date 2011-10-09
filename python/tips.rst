Misc Python Tips
================

===========
EasyInstall
===========

Use ``--find_links`` or ``-f`` options to look in local directories::

    $ easy_install -f ``$HOME/cache`` Django

will look in ``$HOME/cache`` first when installing Django. Or setup config file in $HOME/.pydistutils.cfg::

    $ cat -> $HOME/.pydistutils.cfg
    [easy_install]
    find_links = /home/kamal/cache
    ^C

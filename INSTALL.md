INSTALL
=======

Installation on "Ubuntu 11.04"
------------------------------

First install autoconf if not present

    sudo apt-get install autoconf

cd in the pushpool dir and call autoconf

    autoconf

if error: possibly undefined macro: AM_INIT_AUTOMAKE
you must call aclocal in front of autoconf

    aclocal
    autoconf







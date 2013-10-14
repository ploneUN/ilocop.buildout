ILO Community of Practice Buildout
===================================

Provides functionalities needed for the infrastructure of:

* APYouthnet - http://apyouthnet.ilo.org/

* APGreenJobs - http://apgreenjobs.ilo.org/

* APMagnet - http://apmagnet.ilo.org/

* APSkills - http://apskills.ilo.org/

* APIRNet - http://apirnet.ilo.org/

* APFlare - http://apflare.ilo.org/


Requirements
-------------

* A working Python2.6 installation on a Linux/\*NIX

* libjpeg-devel, zlib-devel

* ejabberd-2.1.12

Installation
-------------


Development mode::

    git clone https://github.com/ploneUN/ilocop.buildout
    cd ilocop.buildout
    python2.6 bootstrap.py
    ./bin/buildout -vvvvv 

Deployment mode::

    git clone https://github.com/ploneUN/ilocop.buildout
    cd ilocop.buildout
    python2.6 bootstrap.py
    ./bin/buildout -vvvv -c deployment.cfg

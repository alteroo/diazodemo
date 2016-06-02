Quick Start
============

::


    git clone git@github.com:alteroo/diazodemo.git
    cd diazodemo
    virtualenv .
    . bin/activate
    bin/pip install -r requirements.txt
    bin/buildout
    

To test it out::

    bin/paster serve --reload proxy.ini


It will launch on port 5000

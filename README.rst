uname
=====

Get Information About Current Linux Kernel With Assembly & C Language

Install Dependency (Fedora)
===========================
::

    yum install nasm


Install Dependency (Ubuntu)
===========================
::

    apt install nasm

Building and Installing
=======================
::

	./setup.py build install

Installing Through PyPi
=======================
::

	pip3 install uname

Python Sample Usage
===================
::

    >>> import uname
    >>> uname.get(uname.SYSNAME)
    Linux
    >>> uname.get(uname.NODENAME)
    ubuntu
    >>> uname.get(uname.RELEASE)
    5.4.0-56-generic
    >>> uname.get(uname.VERSION)
    #62-Ubuntu SMP Mon No
    >>> uname.get(uname.MACHINE)
    x86_64
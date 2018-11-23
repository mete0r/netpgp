netpgp
======

This repository hosts personal modifications on Alistair Crooks' netpgp_.

.. _netpgp: http://www.netpgp.com/

Summary of modifications:

- Some tweaks to compile on Debian GNU/Linux
- .gitignore
- A README (this file)


Quick build instruction
-----------------------

To build and install in an isolated directory with PIC only::

   mkdir build
   cd build
   $(realpath ../configure) --prefix=$(realpath .) --with-pic
   make install

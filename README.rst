manylinux-gcc10.1
=================
The goal of this manylinux repo is to allow a quick docker deploy of manylinux2010 and manylinux2014 with GCC 10.1
essentially enabling C++20 (and latest features).

The submodule ``manylinux-reference``, as per the name, is a simple reference tracker and will be used as an
updating trigger for the ``manylinux-gcc10.1`` docker.

GCC and G++ 10.1 are installed into ``/usr/local/bin`` as gcc and g++.


Images
------

manylinux2010-gcc10.1
~~~~~~~~~~~~~~~~~~~~~

x86-64 image: ``p0nkz/manylinux2010-x86_64-gcc10.1``

.. image:: https://img.shields.io/docker/image-size/p0nkz/manylinux2010-x86_64-gcc10.1   :alt: Docker Image Size (latest by date)

manylinux2014-gcc10.1
~~~~~~~~~~~~~~~~~~~~~

x86-64 image: ``p0nkz/manylinux2014-x86_64-gcc10.1``

.. image:: https://img.shields.io/docker/image-size/p0nkz/manylinux2014-x86_64-gcc10.1   :alt: Docker Image Size (latest by date)

===================
OEIS GF Package
===================

This package is designed as as simple `SageMath <http://www.sagemath.org>`_ package 
for OEIS generating functions. Currently it supports the ordinary generating functions only.

Installation
------------

Local install from source
^^^^^^^^^^^^^^^^^^^^^^^^^

Download the source from the github and run this command from the repo root::

    $ sage  -pip install --upgrade --no-index -v .

Equivalently, you can use the ``Makefile`` install command::

    $ make install

Install from PyPI
^^^^^^^^^^^^^^^^^^

TODO: distribute on PyPI.

Usage
-----

Once the package is installed, you can use it on Sage with::

    sage: from oeis_gf import 
    sage: A000027()['ogf']
    [x/(x - 1)^2]


Documentation
-------------

You can use the Sage ``Sphinx`` installation to generate the documentation of the
package::

    $ cd docs
    $ sage -sh -c "make html"

Or for short::

    $ make doc

Travis CI integration
---------------------

TODO;

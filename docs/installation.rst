.. highlight:: shell

============
Installation
============


Stable release
--------------

To install pypkgs_yh, run this command in your terminal:

.. code-block:: console

    $ pip install -u pypkgs_yh

This is the preferred method to install pypkgs_yh, as it will always install the most recent stable release.

If you don't have `pip`_ installed, this `Python installation guide`_ can guide
you through the process.

.. _pip: https://pip.pypa.io
.. _Python installation guide: http://docs.python-guide.org/en/latest/starting/installation/


From sources
------------

The sources for pypkgs_yh can be downloaded from the `Github repo`_.

You can either clone the public repository:

.. code-block:: console

    $ git clone git://github.com/yhchen20/pypkgs_yh

Or download the `tarball`_:

.. code-block:: console

    $ curl  -OL https://github.com/yhchen20/pypkgs_yh/tarball/main

Once you have a copy of the source, you can install it. The method of installation will depend on the packaging library being used.

For example, if `setuptools` is being used (a setup.py file is present), install pypkgs_yh with:

.. code-block:: console

    $ python setup.py install

If `poetry` is being used (poetry.lock and pyproject.toml files are present), install pypkgs_yh with:

.. code-block:: console

    $ poetry install


.. _Github repo: https://github.com/yhchen20/pypkgs_yh
.. _tarball: https://github.com/yhchen20/pypkgs_yh/tarball/master

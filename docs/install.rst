Install
=======

By using pip:

.. code-block:: sh

    $ pip install pyftpdlib

From sources:

.. code-block:: sh

    $ git clone git@github.com:giampaolo/pyftpdlib.git
    $ cd pyftpdlib
    $ python3 setup.py install

You might want to run tests to make sure pyftpdlib works:

.. code-block:: sh

    $ make test
    $ make test-contrib


Additional dependencies
-----------------------

`PyOpenSSL <https://pypi.python.org/pypi/pyOpenSSL>`__, to support
`FTPS <http://pyftpdlib.readthedocs.io/tutorial.html#ftps-ftp-over-tls-ssl-server>`__:

.. code-block:: sh

    $ pip install PyOpenSSL

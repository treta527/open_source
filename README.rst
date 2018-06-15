===========
Open Source
===========


.. image:: https://img.shields.io/travis/goanpeca/open_source.svg
        :target: https://travis-ci.org/goanpeca/open_source


.. image:: https://codecov.io/gh/goanpeca/open_source/branch/master/graph/badge.svg
        :target: https://codecov.io/gh/goanpeca/open_source


A package to test some open source workflows


* Free software: MIT license
* Documentation: https://open-source.readthedocs.io.


Install
-------

* Fork and run from root directory.

.. code-block:: bash

   $ python setup.py develop


Run tests
---------

.. code-block:: bash

   $ pytest tests/ --cov=open_source -v

Use
---

.. code-block:: bash

   $ open_source --help
   $ open_source check_palindrome oso
   $ open_source random_int 0 10
   $ open_source random_letter
   $ open_source random_letter word

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

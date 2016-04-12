========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |coveralls|
        | |landscape| |scrutinizer|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/datafellows/badge/?style=flat
    :target: https://readthedocs.org/projects/datafellows
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/redwardstern/datafellows.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/redwardstern/datafellows

.. |coveralls| image:: https://coveralls.io/repos/redwardstern/datafellows/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/redwardstern/datafellows

.. |landscape| image:: https://landscape.io/github/redwardstern/datafellows/master/landscape.svg?style=flat
    :target: https://landscape.io/github/redwardstern/datafellows/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/datafellows.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/datafellows

.. |downloads| image:: https://img.shields.io/pypi/dm/datafellows.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/datafellows

.. |wheel| image:: https://img.shields.io/pypi/wheel/datafellows.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/datafellows

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/datafellows.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/datafellows

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/datafellows.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/datafellows

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/redwardstern/datafellows/master.svg?style=flat
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/redwardstern/datafellows/


.. end-badges

Learn data with your fellows

* Free software: BSD license

Installation
============

::

    pip install datafellows

Documentation
=============

https://datafellows.readthedocs.org/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox

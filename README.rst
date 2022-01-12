========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-connectors/badge/?style=flat
    :target: https://python-connectors.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/pepomes/python-connectors/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/pepomes/python-connectors/actions

.. |requires| image:: https://requires.io/github/pepomes/python-connectors/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/pepomes/python-connectors/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/pepomes/python-connectors/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/pepomes/python-connectors

.. |version| image:: https://img.shields.io/pypi/v/connectors.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/connectors

.. |wheel| image:: https://img.shields.io/pypi/wheel/connectors.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/connectors

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/connectors.svg
    :alt: Supported versions
    :target: https://pypi.org/project/connectors

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/connectors.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/connectors

.. |commits-since| image:: https://img.shields.io/github/commits-since/pepomes/python-connectors/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/pepomes/python-connectors/compare/v0.0.0...main



.. end-badges

Connectors for various things (market data, exchanges, ...)

* Free software: BSD 2-Clause License

Installation
============

::

    pip install connectors

You can also install the in-development version with::

    pip install https://github.com/pepomes/python-connectors/archive/main.zip


Documentation
=============


https://python-connectors.readthedocs.io/


Development
===========

To run all the tests run::

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

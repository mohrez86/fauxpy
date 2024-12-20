======================
FauxPy documentation
======================

.. meta::
   :google-site-verification: EYJEnxDgQe_QOGhufWaLSL_DjZPlnox075UyuGTVA0E

.. image:: https://badge.fury.io/py/fauxpy.svg
   :target: https://badge.fury.io/py/fauxpy

.. image:: https://img.shields.io/github/license/atom-sw/fauxpy
.. image:: https://static.pepy.tech/badge/fauxpy
   :target: https://pepy.tech/project/fauxpy

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black

.. image:: https://img.shields.io/badge/FauxPy--Test-Repository-2ea44f
   :target: https://github.com/mohrez86/fauxpy-test
   :alt: FauxPy-Test - Repository

.. image:: https://img.shields.io/github/stars/atom-sw/fauxpy?style=social
   :target: https://github.com/atom-sw/fauxpy

.. image:: https://img.shields.io/github/stars/mohrez86/fauxpy?style=social
   :target: https://github.com/mohrez86/fauxpy

FauxPy (pronounced: "foh pie") is an automated fault localization tool for Python programs,
`available as open-source software on GitHub <https://github.com/atom-sw/fauxpy>`_.
This documentation includes instructions to install and use FauxPy.

.. tip::
   We are constantly improving FauxPy and
   welcome your **feedback and suggestions**.
   Share your ideas in our
   `Discussions section <https://github.com/mohrez86/fauxpy/discussions>`_.


Features
========

FauxPy supports seven classic fault-localization techniques in four families:

1. **SBFL** (spectrum-based) techniques Tarantula, Ochiai, and DStar.
2. **MBFL** (mutation-based) techniques Metallaxis and Muse.
3. **PS** (predicate switching) fault localization.
4. **ST** (stack-trace) fault localization.

It supports fault localization
at the level of **statements** (statement-level granularity)
and at the level of **functions** (function-level granularity).

FauxPy is based on dynamic analysis,
and can use tests written in the format of
`Pytest <https://pytest.org>`_,
`Unittest <https://docs.python.org/3/library/unittest.html>`_,
and `Hypothesis <https://hypothesis.works/>`_.

FauxPy in Action
================

Here is a short `demo video <https://www.youtube.com/watch?v=6ooPPiwd79g>`_
of FauxPy in action, presented by
`the developer of FauxPy <https://mohrez86.github.io>`_
at
`USI Università della Svizzera italiana <https://www.usi.ch/en>`_.

.. image:: https://img.youtube.com/vi/6ooPPiwd79g/0.jpg
   :target: https://www.youtube.com/watch?v=6ooPPiwd79g


.. toctree::
   :maxdepth: 1
   :caption: User Guide

   user/installation
   user/getting_started
   user/using_fauxpy
   user/limitations
   user/test_repo
   user/citing_fauxpy_and_references

.. toctree::
   :maxdepth: 1
   :caption: API Documentation

   developer/entry_points

.. API Indices and tables
.. ======================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`

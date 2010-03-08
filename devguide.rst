===========================
  Zabuton Developer Guide
===========================

:Author:    Ben de Groot <yngwin@zabuton.org>
:Copyright: Licensed under the CC-BY-SA 3.0 license

.. contents::
.. sectnum::

Coding Style
============

We follow the accepted coding style and best practices of the languages and
tools we use. Please read and familiarize yourself with these:

- `Qt Coding Style <http://qt.gitorious.org/qt/pages/QtCodingStyle>`_
- `Qt Coding Conventions <http://qt.gitorious.org/qt/pages/CodingConventions>`_
- `PEP8 Style Guide for Python Code <http://www.python.org/dev/peps/pep-0008/>`_

Formatting
----------

- All text files are utf-8 encoded and use Unix line-endings.
- The standard line-length is 80 characters, with occasional continuations
  to a maximum of 100 characters where that makes sense.
- Indentations are 4 spaces per level, no tabs.


Documentation
=============

For documentation in sourcecode files we use Doxygen_. Standalone documents
are written in reStructuredText, which can be converted with tools such as
docutils_ and Sphinx_. This is also used for generating manpages.

.. _Doxygen: http://www.doxygen.org/
.. _docutils: http://docutils.sourceforge.net/
.. _Sphinx: http://sphinx.pocoo.org/


Licensing
=========

We prefer to use GPL-2 (for applications), LGPL-2.1 (for libraries) or CC-BY-SA
3.0 (for documentation and artwork) where applicable. Copies of these licenses
are available in the project repo for convenience. Note that PyQt4 is not LGPL
licensed, so our PyQt4 based code will always be GPL licensed.

..
    vim: syntax=rest:fenc=utf-8:et:ts=4:

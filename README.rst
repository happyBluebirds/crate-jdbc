.. image:: https://cdn.crate.io/web/2.0/img/crate-avatar_100x100.png
   :width: 100px
   :height: 100px
   :alt: Crate.IO
   :target: https://crate.io

.. image:: https://travis-ci.org/crate/crate-jdbc.svg?branch=master
        :target: https://travis-ci.org/crate/crate-jdbc
        :alt: Test

=================
Crate JDBC Driver
=================

.. highlight:: java

This is the JDBC driver for `Crate`_.

Currently we don't provide the testing version of the Crate JDBC driver.
As a workaround, you can build the JDBC driver jar using `Jitpack`_ or
build it from source.

Installation
============

.. note::

   Crate JDBC driver 1.x requires a Crate version equal or greater than 0.38.0
   but lower than 0.56.0.
   Crate JDBC driver 2.x requires a Crate version equal or greater than 0.56.0.

Build JAR from source
---------------------

Clone the repo::

  git clone --recursive https://github.com/crate/crate-jdbc
  cd crate-jdbc

and build a JAR::

   ./gradlew jar

or build a jar including all dependencies::

   ./gradlew standaloneJar

Afterwards a JAR file of the current version exists under ``build/lib``.

Contributing
============

This project is primarily maintained by `Crate.io`_, but we welcome community
contributions!

See the `developer docs`_ and the `contribution docs`_ for more information.

Help
====

Looking for more help?

- Read `the project documentation`_
- Check `StackOverflow`_ for common problems
- Chat with us on `Slack`_
- Get `paid support`_

.. _contribution docs: CONTRIBUTING.rst
.. _Crate.io: http://crate.io/
.. _developer docs: DEVELOP.rst
.. _the project documentation: https://crate.io/docs/projects/crate-jdbc/
.. _StackOverflow: https://stackoverflow.com/tags/crate
.. _paid support: https://crate.io/pricing/
.. _Slack: https://crate.io/docs/support/slackin/

.. _Crate: https://github.com/crate/crate
.. _Jitpack: https://jitpack.io/#crate/crate-jdbc

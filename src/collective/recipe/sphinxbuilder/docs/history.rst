=======
Changes
=======

1.0+md.2 (unreleased)
=====================

- Nothing changed yet.


1.0+md.1 (2018-02-23)
=====================

  - Python 3 support.


0.8.3 (2015-02-13)
==================

  - Add support for environment variables in the generated Makefile.

0.8.2 (2013-11-28)
==================

  - Prevent a warning when installing with python 3 [reinout]

0.8.1 (2013-11-27)
==================

  - Add Python 3 classifier

0.8.0 (2013-11-27)
==================

  - Added python 3 support [reinout]

0.7.4 (2013-11-15)
==================

  - Update to Buildout 2
  - Cleanup the code to make PEP8 tool happy

0.7.3 (2013-02-16)
==================

  - patch sphinx-build script to terminate with sys.exit()
  - add warnings-html makefile option
  - install sphinx-apidoc and sphinx-autogen scripts
  - rename all txt files to rst ones

0.7.2 (2012-10-22)
==================

  - requires Sphinx >= 1.1

0.7.1 (2012-04-29)
==================

  - Add the epub output.
  - Fixed tests:
    - Use required package versions during tests
    - Use standard `doctest` instead of `zope.testing.doctest`.

0.7.0 (2010-09-10)
==================

  - requires Sphinx >= 1.0

0.6.3.3 (2010-07-15)
====================

  - added `doctest` option to recipe's `output` options (tseaver)

  - relaxed required version of Sphinx to allow versions later than
    0.6.4 (but still less than 0.7dev).

0.6.3.2 (2010-02-08)
====================

  - fixed interpreter options [iElectric]

0.6.3.1 (2009-09-25)
====================

  - problems with previous release [garbas]

0.6.3 (2009-09-09)
==================

  - update to Sphinx 0.6.3 [garbas]
  - simplify sphinxbuilder [garbas]
  - update documentation [garbas]
  - interpreter options [iElectric]
  - added logging [iElectric]

0.5.0 (2008-12-06)
==================

 - Making it compatible with latest sphinx 0.5 [Rok Garbas]
 - Allow for specifying 'product_directories' in order to be able to
   document old-style Zope Products. [Sidnei]

0.2.1 (2008-11-18)
==================

 - Manifest file fixed and making fix release [Rok Garbas]

0.2.0 (2008-11-11)
==================

 - source tree generated every time under
   parts/<buildout-section-name> [Rok Garbas]
 - finds conf options, source, static and template files using
   entry_point 'collective.recipe.sphinxbuilder' [Rok Garbas]
 - custom source folder at docs/source [Rok Garbas]
 - build section moved to docs/html, docs/latex [Rok Garbas]

0.1.1 (2008-09-11)
==================

 - Using a sphinx-build local to the environment [Tarek]

0.1.0 (2008-09-10)
==================

 - Initial implementation [Tarek Ziade]
 - Created recipe with ZopeSkel [Tarek Ziade].

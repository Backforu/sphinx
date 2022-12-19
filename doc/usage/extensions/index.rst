==========
Extensions
==========

Since many projects will need special features in their documentation, Sphinx
allows adding "extensions" to the build process, each of which can modify
almost any aspect of document processing.

This chapter describes the extensions bundled with Sphinx.  For the API
documentation on writing your own extension, refer to :ref:`dev-extensions`.


.. _builtin-extensions:

Built-in extensions
-------------------

These extensions are built in and can be activated by respective entries in the
:confval:`extensions` configuration value:


   import sys, os

   sys.path.append(os.path.abspath('exts'))

   extensions = ['foo']

You can also install extensions anywhere else on ``sys.path``, e.g. in the
``site-packages`` directory.

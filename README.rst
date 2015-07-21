Py4J for Eclipse
================

Py4J for Eclipse enables Python programs running in a Python interpreter to
dynamically access Java objects in a Java Virtual Machine.

This project provides basic plug-ins to interact with Eclipse. Once the
plug-ins are installed with Eclipse, you can access the running Eclipse
instance from Python.

This is the source repository of Py4J for Eclipse projects. Please visit the
`Py4J homepage <http://www.py4j.org>`_ for more information.

For help, register and then post to the Py4J mailing list at
``py4j-users at lists dot sourceforge dot net``


STRUCTURE OF PY4J REPOSITORIES
==============================

The py4j-eclipse project uses the py4j project as a git submodule to prevent
duplicating source files. When cloning py4j-eclipse, always include the
submodules:

.. code-block:: bash

    $ git clone --recursive git@github.com:bartdag/py4j.git

LICENSE
=======

Py4J for Eclipse is distributed with the BSD 3-Clause license. See LICENSE.txt
for more information.


CONTRIBUTING
============

We are always happy to receive code contributions, bug reports, and
documentation fixes. Please visit the `contributing guide
<http://www.py4j.org/contributing.html>`_ for more
information.

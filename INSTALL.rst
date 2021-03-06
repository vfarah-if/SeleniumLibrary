=============================
Selenium Library Installation
=============================

Selenium Library distribution contains the actual library code, Selenium
server as a JAR package and Selenium Python bindings.

SeleniumLibrary 2.9.2 downloads are hosted at `PyPI
<https://pypi.python.org/pypi/robotframework-seleniumlibrary>`_.
Older releases can be found from the old `Google Code download page
<http://code.google.com/p/robotframework-seleniumlibrary/downloads/list>`_.

Preconditions
-------------

Selenium tool requires Java runtime version 1.5 or newer.

Selenium Library itself supports all Python and Jython interpreters that are
supported by Robot Framework.

Installing using pip
--------------------

If you have pip installed, you can install SeleniumLibrary by running::

    pip install --upgrade robotframework-seleniumlibrary

Installing from source
----------------------

The source code can be got either as a source distribution or as a checkout
from our version control system. The installer requires Python version 2.4 or
newer. Selenium Library is installed from source by typing following command::

    python setup.py install 

In most linux systems, you need to have root privileges for installation.

Uninstallation is achieved by deleting the installation directory and its
contents from the file system. The default installation directory is
`[PythonLibraries]/site-packages/SeleniumLibrary`.

Using Windows installer
-----------------------

Windows installer is the only available binary installer. It is
enough to double-click the installer and follow the instructions.

Selenium Library can be uninstalled using Add/Remove Programs utility from
Control Panel. 

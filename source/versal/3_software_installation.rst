-  **
-  **
-  **

Install dependencies

-  **
-  **
-  **

Management systems
~~~~~~~~~~~~~~~~~~

To install the software dependencies required for mdid3 to run, use the
system-specific methods listed below. Experienced developers or system
admins may take issue with some details - in many cases the way
described is not "the only way" but rather "just a way" - in some cases
it's aiming to be describe simplest way. Feedback and alternative
procedures are welcome, please feel free to submit them.

**Package Management System/Command**

-  **
-  **
-  **

replace file

|image0|

No image chosen

-  **
-  **
-  **

bad table 1

| UbuntuRed HatMac OS XWindows 2008 or
other\ `apt-get <https://help.ubuntu.com/community/AptGet/Howto>`__
Redhat -
`yum <http://www.ibm.com/developerworks/linux/library/l-lpic1-v3-102-5/>`__
`rhel
5 <https://access.redhat.com/knowledge/docs/en-US/Red_Hat_Enterprise_Linux/5/html/Deployment_Guide/c1-yum.html>`__
\| `rhel
6 <https://access.redhat.com/knowledge/docs/en-US/Red_Hat_Enterprise_Linux/6/html/Deployment_Guide/ch-yum.html>`__
`homebrew <http://mxcl.github.com/homebrew/>`__
| download installers & compile sourceNone (true? any dissent?).
| Download installers or executables.

-  **
-  **
-  **

bad table 2 - md
^^^^^^^^^^^^^^^^

+----------+-------------+------------+------------------+-------------------------+
|          | Ubuntu      | Red Hat    | Mac OS X         | Windows 2008 or other   |
+==========+=============+============+==================+=========================+
| python   | installed   | python26   | installed        | Python 2.7.3            |
+----------+-------------+------------+------------------+-------------------------+
| git      | git-core    | git-core   | Github for Mac   | Github for Windows      |
+----------+-------------+------------+------------------+-------------------------+

--------------

-  **
-  **
-  **

Software package installation

-  **
-  **
-  **

Below is a matrix of the software dependencies required for mdid3 to run
correctly. In general, software installed via a package manager like apt
or yum will be displayed as ``package-name`` whereas a downloadable
installer, binary or downloadable source will be a `text link <#>`__

Apt and Yum generally need to be run via sudo, but the Mac OS X package
manager homebrew is designed specifically to **not** use sudo (assumedly
because the normative mac user account has installation privileges). So
to install ``packageX``, use the commands:

-  **
-  **
-  **

replace file

|image1|

No image chosen

-  **
-  **
-  **

apt (Ubuntu)yum (Red Hat)homebrew (Mac OS X)sudo apt-get install
packageXsudo yum install packageX brew install packageX

-  **
-  **
-  **

--------------

Optionally, package managers can be given a list of packages, and be
told to say "yes" to every question, and the human being installing the
software can do something important, like drink coffee. A
copy/paste-able single command will be presented at the bottom of the
matrix.

-  **
-  **
-  **

|  UbuntuRed HatMac OS XWindows 2008 or
otherpythoninstalledpython26\ `installed <http://mac.github.com>`__\ Python
2.7.3
| (`32-bit <http://www.python.org/ftp/python/2.7.3/python-2.7.3.msi>`__)
\|
(`64-bit <http://www.python.org/ftp/python/2.7.3/python-2.7.3.amd64.msi>`__)git
git-coregit-core\ `Github for Mac <http://mac.github.com>`__\ `Github
for Windows <http://windows.github.com>`__

-  **
-  **
-  **

--------------

Ubuntu
~~~~~~

::

    sudo apt-get -y upgrade && install

    sudo apt-get  -y install openjdk-6-jre-headless python-setuptools libjpeg62-dev unixodbc unixodbc-dev freetds-dev tdsodbc python-dev libmysqlclient16-dev  python-ldap python-memcache memcached libapache2-mod-wsgi g++ mysql-server

Redhat Packages
~~~~~~~~~~~~~~~

TBD

Mac OS X homebrews
~~~~~~~~~~~~~~~~~~

TBD

Windows Installers
~~~~~~~~~~~~~~~~~~

TBD

.. |image0| image:: //static.versal.com/restapi/assets/cc3ab56f-5eeb-4a7b-b8f5-2b483f17d790
.. |image1| image:: //static.versal.com/restapi/assets/6d464765-3ea4-4994-bf4b-4bb0b5ef2a5c

EPEL rpm repo
^^^^^^^^^^^^^

::

    sudo rpm -Uvh http://download.fedora.redhat.com/pub/epel/5/i386/epel-release-5-4.noarch.rpm

    rpm -Uvh http://yum.chrislea.com/centos/5/i386/chl-release-5-3.noarch.rpm

    rpm --import /etc/pki/rpm-gpg/RPM-GPG-KEY-CHL

git
^^^

``sudo yum install git-core``

::

    sudo yum install python26 python26-devel python26-setuptools java-1.6.0-openjdk  libjpeg-devel unixODBC unixODBC-devel freetds-devel  MySQL-python26 python-ldap python-memcached mod_wsgi gcc-c++ pyodbc 

if mysql is on the same server
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    sudo yum install mysql-server -y  

add alias for running easy\_intall & pip via python26
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    alias easy26='sudo python26 /usr/lib/python2.6/site-packages/easy_install.py'

    easy26 pip

optional, but do yourself a favor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    pip install virtualenv

    sudo mkdir /var/local/virt
    sudo chown mdid:staff virt
    virtualenv-2.6 -v --no-site-packages virt/mdid3

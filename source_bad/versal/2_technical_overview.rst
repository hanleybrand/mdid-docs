MDID3 is a `django web application <https://docs.djangoproject.com/>`__
that requires at minimum to run:

-  a web server capable of serving WSGI applications, either using
   `mod\_wsgi <http://code.google.com/p/modwsgi/>`__ with `Apache HTTP
   Server <http://httpd.apache.org>`__ or other alternative that works
   similarly
   (e.g.\ `uWSGI <https://github.com/unbit/uwsgi-docs#readme>`__ &
   `nginx <http://wiki.nginx.org/Main>`__) or `Microsoft
   IIS <http://www.iis.net>`__ with
   `pyisapie <http://sourceforge.net/apps/trac/pyisapie>`__

   -  the webserver needs to be able to run python as a daemon for
      worker processes like image processing, data import, etc.

-  a `Apache Solr <http://lucene.apache.org/solr/>`__ server for search
-  a memory object caching server like
   `memcached <http://memcached.org>`__ or `Couchbase
   Server <http://www.couchbase.com/couchbase-server/overview>`__
-  a database server - all known installations are currently based in
   `mySQL <http://www.mysql.com/downloads/mysql/>`__ or MS SQL Server,
   but Postgress should theoretically work - let us know, won't you?
-  `django 1.2.3 <https://docs.djangoproject.com/en/1.2/>`__ is the most
   used, but 1.2.7 looks stable. It is possible that it is fully
   compatible with Django 1.4, but that is based solely on `this repo's
   commit
   notes <https://github.com/jcarbaugh/rooibos/commit/f80aca5c9614439735a9c7e93115bdaaff26c396>`__

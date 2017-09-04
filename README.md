
Kylin DBAPI Driver and Sqlalchemy Dialect for Apache Superset
==============================

Usage 
------

To use it in Superset, fill SQLAlchemy URI with::

     kylin://User:Password@Host[:7070]/kylin/api?project=your_project_name

Acknowledgement
---------------

This plugin is based on Wu Xiang's Kylin DBAPI Driver and Sqlalchemy Dialect and customized to connect Superset with Kylin. The modification mainly follows the guides from http://bigdata.51cto.com/art/201703/535777.htm and https://github.com/YorkeCao/pykylin4superset with minor fixes and improvement.


Original Page
===============================

Installation
------------

To install this driver run::

    $ pip install pykylin

or from source::

    $ pip install -r ./requirements.txt
    $ python setup.py install


More info
---------

 * http://kylin.incubator.apache.org/
 * http://www.sqlalchemy.org/


Authors
-------

 * Wu Xiang

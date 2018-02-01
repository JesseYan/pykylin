
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

~~To install this driver run~~

~~$ pip install pykylin~~

or from source
```
$ pip install -r ./requirements.txt
$ python setup.py install
```

More info
---------

 * http://kylin.incubator.apache.org/
 * http://www.sqlalchemy.org/


Fixed bug by JesseYan
---------
* 229bfc315ffc70d7b1c5190f6f68f50fcb28c872	更新setup.py
* 59e7913da2bd8c34853c9cf0febb03632b69cdb5	修改BUG：get_table_names


Authors
-------

 * Wu Xiang
 * Jesse Yan

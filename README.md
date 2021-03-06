# mysqlclient

[![Build Status](https://secure.travis-ci.org/PyMySQL/mysqlclient-python.png)](http://travis-ci.org/PyMySQL/mysqlclient-python)

This is a fork of [MySQLdb1](https://github.com/farcepest/MySQLdb1).

This project adds Python 3 support and bug fixes.
I hope this fork is merged back to MySQLdb1 like distribute was merged back to setuptools.

## Install

### Prerequisites

You may need to install the Python and MySQL development headers and libraries like so:

`sudo apt-get install python-dev libmysqlclient-dev`  # Debian / Ubuntu

`sudo yum install python-devel mysql-devel`  # Red Hat / CentOS

On Windows, there are binary wheel you can install without MySQLConnector/C or MSVC. 


### Install from PyPI

`pip install mysqlclient`

NOTE: Wheels for Windows may be not released with source package. You should pin version
in your `requirements.txt` to avoid trying install source newest pacakge.


### Install from source

1. Download source by `git clone` or [zipfile](https://github.com/PyMySQL/mysqlclient-python/archive/master.zip).
2. Customize `site.cfg`
3. `python setup.py install`

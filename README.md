# Anomaly_Detection


Mypy: Optional Static Typing for Python
=======================================

[![Build Status](https://api.travis-ci.org/python/mypy.svg?branch=master)](https://travis-ci.org/python/mypy)
[![Chat at https://gitter.im/python/typing](https://badges.gitter.im/python/typing.svg)](https://gitter.im/python/typing?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)


Got a question? Join us on Gitter!
----------------------------------

We don't have a mailing list; but we are always happy to answer
questions on [gitter chat](https://gitter.im/python/typing).  If you are
sure you've found a bug please search our issue trackers for a
duplicate before filing a new issue:

- [Unsupervised Anomaly Detection with Isolation Forest - Elena Sharova](https://www.youtube.com/watch?v=5p8B2Ikcw-k)
- [typeshed tracker](https://github.com/python/typeshed/issues)
  for issues with specific modules


What is mypy?
-------------

Mypy is an optional static type checker for Python.  You can add type
hints ([PEP 484](https://www.python.org/dev/peps/pep-0484/)) to your
Python programs, and use mypy to type check them statically.
Find bugs in your programs without even running them!

You can mix dynamic and static typing in your programs. You can always
fall back to dynamic typing when static typing is not convenient, such
as for legacy code.

Here is a small example to whet your appetite (Python 3):


Tests
-----

The basic way to run tests:

    $ pip3 install -r test-requirements.txt
    $ ./runtests.py

For more on the tests, see [Test README.md](test-data/unit/README.md)



<img src="http://mypy-lang.org/static/mypy_light.svg" alt="mypy logo" width="300px"/>


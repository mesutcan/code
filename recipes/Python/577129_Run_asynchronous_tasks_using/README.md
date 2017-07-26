###Run asynchronous tasks using coroutines

Originally published: 2010-03-19 10:11:16
Last updated: 2010-08-06 16:16:20
Author: Arnau Sanchez

This recipe shows a simple, transparent (and hopefully pythonic) way of running asynchronous tasks when writing a event-driven application (i.e. GUI). The aim is to allow a programmer to write time-consuming functions (usually IO-bound, but not only) with sequential-looking code, instead of scattering the logic over a bunch of callbacks. We will take advantage of the coroutines introduced in Python 2.5 (see http://www.python.org/dev/peps/pep-0342). 
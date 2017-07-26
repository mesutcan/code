###Multiprocess-safe logging file-handler + interprocess RLock

Originally published: 2010-09-19 01:34:53
Last updated: 2010-09-22 17:30:10
Author: Jan Kaliszewski

A Python 2.x/3.x-compatibile **multiprocess-safe logging file-handler** (logging.FileHandler replacement, designed for logging to a single file from multiple independent processes) together with a simple **interprocess recursive lock** -- universal abstract classes + Unix/Linux implementation.
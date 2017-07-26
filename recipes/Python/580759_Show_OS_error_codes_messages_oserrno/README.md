###Show OS error codes and messages from the os.errno module

Originally published: 2017-03-01 17:16:45
Last updated: 2017-03-01 17:18:23
Author: Vasudev Ram

This recipe is a simple Python introspection utility that displays the defined OS error codes and messages (that Python knows about) from the os.errno module. It works for both Python 2 and Python 3. For each kind of OS error defined in Python, it will display a serial number, the error code, and the corresponding error name, and English error message. E.g. the first few lines of its output are shown below:
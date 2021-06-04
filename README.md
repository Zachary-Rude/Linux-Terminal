# **Linux Terminal**

This is a Chromebook-compatible, Chromebook-style Linux terminal, written in Python.

## __Source Code__
```python
import os

pink = "\033[0;31m"
white = "\033[0;37m"
while True:
    print(pink + "chromeready@penguin:~$", end=" ")
    cmd = input(white)
    os.system(cmd)
```

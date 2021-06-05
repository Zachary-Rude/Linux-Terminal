# **Linux Terminal**

This is the terminal fro Ubuntu, now available on every device!
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

# Termux [![Python 3.x](https://img.shields.io/badge/PYTHON-3.X-blueviolet?style=for-the-badge)](http://www.python.org/download/) [![MIT License](https://img.shields.io/badge/LICENSE-MIT-brightgreen?style=for-the-badge)](https://github.com/AXDZ/termux/blob/master/LICENSE)
Python based termux api wrapper

# Functions
As of right now it only has the following features

- [x] Copy - copies the provided text to the clipboard
- [x] Wifi - lets you turn on/off the wifi
- [x] Flashlight - lets you turn on/off the flashlight
- [x] Toast - lets you display toast message to the user

And more is to be added in the future

# Installation

This packages has been uploaded to pypi which means that you can install it by simply using pip as following

```pip install termux```

# Usage

Copy example:
```
from termux.api import copy

copy('This is an example of copy')
```

Flashlight example:
```
from termux.api import torch

torch(True)
```

Wifi example:
```
from termux.api import wifi

wifi(True)
```

Example of toast message with most of the options:
```
from termux.api import toast

toast('This is an example', s=False, attr='bottom')
```


## Built with ❤️ by

* [Aldas](https://github.com/AXDZ) - The creator of the package

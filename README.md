# taglogger

A simple logger that adds tags to log messages to make it easier to filter them.

![License: MIT](https://img.shields.io/github/license/joaompinto/taglogger?style=for-the-badge&color=%23007ec6)
[![PyPi](https://img.shields.io/pypi/v/lxcraft.svg?style=for-the-badge&color=%23007ec6)](https://pypi.python.org/pypi/taglogger)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg?style=for-the-badge)](https://github.com/ambv/black)

![alt text](imgs\taglogger.png "Title")

## Installation

```bash
pip install taglogger
```

## Usage

```python
# main.py
from taglogger import tlog

tlog("traffic", "There is a traffic jam")
```

```bash
$ DEBUG=traffic python main.py
[traffic] There is a traffic jam
```


[![PyPi](https://img.shields.io/pypi/v/taglogger.svg?style=flat-square)](https://pypi.python.org/pypi/taglogger)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg?style=flat-square)](https://github.com/ambv/black)

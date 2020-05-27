# os-release

[![PyPI](https://img.shields.io/pypi/v/os-release)](https://pypi.org/project/os-release)
[![Documentation Status](https://readthedocs.org/projects/python-os-release/badge/?version=latest)](https://python-os-release.readthedocs.io/en/latest/?badge=latest)

_os-release_ is a simple Python module for reading systemd's `os-release` information on modern Linux distributions.

It parses the contents of systemd's `os-release`
([os-release(5)](https://www.freedesktop.org/software/systemd/man/os-release.html)) files:
`/etc/os-release` or `/usr/lib/os-release`.

## Installation

_os-release_ is available on [PyPI](https://pypi.org/project/os-release).

Add it to your projects `setup.py` `install_requires`:

    install_requires=['os-release']
 
or install it directly via `pip`:

    $ pip install os-release
    
Alternatively, clone this Git repository and run:

    $ python setup.py install
    
## Documentation:

Documentation for _os-release_ is available on [Read the Docs](https://python-os-release.readthedocs.io/en/latest/).
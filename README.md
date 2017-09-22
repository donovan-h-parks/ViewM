# ViewM

**[This project is in active development and not currently recommended for public use.]**

[![version status](https://img.shields.io/pypi/v/viewm.svg)](https://pypi.python.org/pypi/viewm)
[![downloads](https://img.shields.io/pypi/dm/viewm.svg)](https://pypi.python.org/pypi/viewm)

ViewM is a software toolkit for visualizing functional modules that aid in the biological interpretation of genomes. It supports visualization of KEGG modules and user-defined sets of genes described using KEGG-style logical expressions. The primary design goal of ViewM is to provide a compact visual representation of KEGG-style logical expressions suitable for showing the presence and absence of genes across multiple genomes. 

## Installation

ViewM can be installed using [pip](https://pypi.python.org/pypi/viewm):
```
> sudo pip install viewm
```

ViewM makes use of the [svgwrite](https://svgwrite.readthedocs.io) python package.

## Quick Start

The functionality provided by ViewM can be accessed through the help menu:
```
> viewm -h
```

Usage information about specific functions can also be accessed through the help menu, e.g.:
```
> viewm draw –h
```

## Cite

If you find this package useful, please cite this git repository (https://github.com/dparks1134/ViewM)


## Copyright

Copyright © 2017 Donovan Parks. See LICENSE for further details.


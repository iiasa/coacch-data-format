# The COACCH data format for climate change impact analysis

Copyright (c) 2021 IIASA

This repository is licensed under the [MIT License](LICENSE).

![License](https://img.shields.io/github/license/iiasa/coacch-data-format)
[![python](https://img.shields.io/badge/python-3.7_|_3.8_|_3.9-blue?logo=python&logoColor=white)](https://github.com/IAMconsortium/pyam)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Overview

[<img src="./_static/coacch-logo.jpg" width="200" align="right" alt="pyam" />](https://www.coacch.eu)

This repository contains tutorials and guidance for using the **pyam** package
to work with the data format used in the Horizon 2020 project [COACCH](https://www.coacch.eu).

## Dependencies

[<img src="./_static/pyam.png" width="500" align="right" alt="pyam" />](https://pyam-iamc.readthedocs.io)

The Python package **pyam** was developed to facilitate working with timeseries data
following the data format developed by the IAMC;
however, it can also support other applications like the COACCH project data format.

Features include validation of values, aggregation and downscaling of data,
and import/export (i/o) with various file formats (`xlsx`, `csv`, ...)
and table layouts (wide vs. long data).

[Read the docs](https://pyam-iamc.readthedocs.io) for more information!

### TL;DR - Quick install

You can install **pyam** and all its dependencies via the
[Python  Package Index (PyPI)](https://pypi.org/project/pandas)
and on [Conda](https://docs.conda.io/en/latest/).

```sh
# conda
conda install -c conda-forge pyam
```

```sh
# PyPI
pip install pyam-iamc
```

## Building the docs

Run Sphinx to build the docs!

    make --directory=doc html

The rendered html pages will be located in `doc/build/html/index.html`.

## Funding acknowledgement

<img src="./_static/EU-logo-300x201.jpg" width="80" height="54" align="left" alt="EU logo" />
This project has received funding from the European Union’s Horizon 2020<br />
research and innovation programme under grant agreement No. 776479.

[![PyPI version](https://badge.fury.io/py/ib_dl.svg)](https://badge.fury.io/py/ib_dl)
[![Build Status](https://api.travis-ci.org/tibkiss/ib_dl.svg?branch=maste´r)](https://travis-ci.org/tibkiss/ib_dl)
[![Docker Build Status](https://img.shields.io/docker/build/tibkiss/ib_dl.svg)](https://hub.docker.com/r/tibkiss/ib_dl/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# Historical market data downloader 
Utility to download historical market data from Interactive Brokers.
The heavy lifting is done by [ib_insync](https://github.com/erdewit/ib_insync) project.

## Requirements
 * Python 3.6
 * [ib_insync](https://github.com/erdewit/ib_insync)
 * [IB's TWS API](http://interactivebrokers.github.io)
 
## Usage
 * Install with pip: `pip install ib_dl`
 * Start TWS, enable API access
 * Download data: `ib_dl SPY "1 M" /path/to/dest/dir localhost:7492:999`

For further details see the help screen.

## License
[Apache License Version 2.0](http://www.apache.org/licenses/)
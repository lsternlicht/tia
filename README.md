# tia: Toolkit for integration and analysis

## Overview
TIA is a toolkit that provides bloomberg data access, easier pdf generation, backtesting functionality,
technical analysis functionality, return analysis, and few windows utils.

## Examples

Bloomberg API
- [v3 api](http://nbviewer.ipython.org/github/bpsmith/tia/blob/master/examples/v3api.ipynb)
- [Data Manager] (http://nbviewer.ipython.org/github/bpsmith/tia/blob/master/examples/datamgr.ipynb)

Simple Trade and Portfolio Model
- [model](http://nbviewer.ipython.org/github/bpsmith/tia/blob/master/examples/model_usage.ipynb)

PDF Generation (using reportlab)
- [pdf generation](http://nbviewer.ipython.org/github/bpsmith/tia/blob/master/examples/rlab_usage.ipynb)

Technical Analysis
- [pure python and ta-lib](http://nbviewer.ipython.org/github/bpsmith/tia/blob/master/examples/ta.ipynb)

Backtest
- [backtest with yahoo data](http://nbviewer.ipython.org/github/bpsmith/tia/blob/master/examples/backtest.ipynb)
- backtest with bbg data and pdf (Soon)


## Dependencies
- Python 2.7

### Mandatory
- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)

### Recommended
- [matplotlib](http://matplotlib.sourceforge.net)

### Optional
- [reportlab](http://www.reportlab.com/)
- [ta-lib](http://mrjbq7.github.io/ta-lib/)
- [bloomberg](http://www.bloomberglabs.com/api/libraries/)


##Installation

To install tia, simply:

.. code-block:: bash

    $ pip install tia

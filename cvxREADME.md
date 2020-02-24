###HFACQuant - Convex Optimization

This repository currently contains a clone of cvxportfolio.
Below is a copy of README.md from cvxportfolio:


`cvxportfolio`
=============
[![CVXportfolio on PyPI](https://img.shields.io/pypi/v/cvxportfolio.svg)](https://pypi.org/project/cvxportfolio/)
[![Build Status](https://travis-ci.org/cvxgrp/cvxportfolio.png?branch=master)](https://travis-ci.org/cvxgrp/cvxportfolio)
[![Coverage Status](https://coveralls.io/repos/github/cvxgrp/cvxportfolio/badge.svg?branch=master)](https://coveralls.io/github/cvxgrp/cvxportfolio?branch=master)
[![Apache 2.0 License](https://img.shields.io/badge/License-APACHEv2-green.svg)](https://github.com/cvxgrp/cvxportfolio/blob/master/LICENSE)

**The documentation of the package is given at [cvxportfolio.org](http://www.cvxportfolio.org/).**

`cvxportfolio` is a python library for portfolio optimization and simulation,
based on the paper [Multi-Period Trading via Convex Optimization](https://web.stanford.edu/~boyd/papers/cvx_portfolio.html).
It is written in Python, its major dependencies are [`cvxpy`](https://github.com/cvxgrp/cvxpy)
and [`pandas`](https://github.com/pandas-dev/pandas).

See the [examples](https://github.com/cvxgrp/cvxportfolio/tree/master/examples) for basic usage.

If you wish to cite CVXPortfolio, please use:
```
@article{BBDKKNS:17,
    author       = {S. Boyd and E. Busseti and S. Diamond and R. Kahn and K. Koh and P. Nystrup and J. Speth},
    title        = {Multi-Period Trading via Convex Optimization},
    journal      = {Foundations and Trends in Optimization},
    year         = {2017},
    month        = {August},
    volume       = {3},
    number       = {1},
    pages        = {1--76},
    publisher    = {Now Publishers},
    url          = {http://stanford.edu/~boyd/papers/cvx_portfolio.html},
}
```

Installation
------------

To install the package:
```
pip install cvxportfolio
```

To test it:

```
pip install nose
nosetests cvxportfolio
```


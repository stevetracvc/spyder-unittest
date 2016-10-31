# spyder-unittest

## Build Status
[![Build Status](https://travis-ci.org/spyder-ide/spyder-unittest.svg?branch=master)](https://travis-ci.org/spyder-ide/spyder-unittest)
[![Build status](https://ci.appveyor.com/api/projects/status/53wqek2p84j73kqq?svg=true)](https://ci.appveyor.com/project/goanpeca/spyder-unittest)
[![CircleCI](https://circleci.com/gh/spyder-ide/spyder-unittest/tree/master.svg?style=shield)](https://circleci.com/gh/spyder-ide/spyder-unittest/tree/master)
[![Coverage Status](https://coveralls.io/repos/github/spyder-ide/spyder-unittest/badge.svg?branch=master)](https://coveralls.io/github/spyder-ide/spyder-unittest?branch=master)
[![Code Issues](https://www.quantifiedcode.com/api/v1/project/cce1ea0d121246ff876d2822e9e3d2a1/badge.svg)](https://www.quantifiedcode.com/app/project/cce1ea0d121246ff876d2822e9e3d2a1)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/spyder-ide/spyder-unittest/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/spyder-ide/spyder-unittest/?branch=master)

## Project information
[![Join the chat at https://gitter.im/spyder-ide/spyder](https://badges.gitter.im/spyder-ide/spyder.svg)](https://gitter.im/spyder-ide/spyder)

## Description
This is a plugin for Spyder that integrates popular unit test
frameworks. It allows you to run tests and view the results.


## Status

This is a work in progress. Only basic functionality is implemented.
At the moment, it only supports the py.test testing framework.

## Installation

See https://github.com/spyder-ide/spyder/wiki/User-plugins but in
short, the following command installs the development version of the
unittest plugin:

```python
pip install git+git://github.com/spyder-ide/spyder-unittest.git
```

The plugin is not yet included in PyPI.

## Usage

The plugin adds an item `Run unit tests` to the `Run` menu in Spyder.
Click on this to run the unit tests. A window pane will pop up with
the results.

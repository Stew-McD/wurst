# Wurst

[![Build Status](https://travis-ci.org/IndEcol/wurst.svg?branch=master)](https://travis-ci.org/IndEcol/wurst) [![Coverage Status](https://coveralls.io/repos/github/IndEcol/wurst/badge.svg?branch=master)](https://coveralls.io/github/IndEcol/wurst?branch=master) [![Docs](https://readthedocs.org/projects/wurst/badge/?version=latest)](https://wurst.readthedocs.io/)

Show how the sausage is made!

Wurst is a python package for linking and modifying industrial ecology models, with a focus on sparse matrices in life cycle assessment. It provides the following:

* Helper functions to filter activities and exchanges
* Helper functions to link exchanges
* Transformation functions to change markets, change input efficiencies, and change emissions
* Data IO with [Brightway2](https://brightwaylca.org/)
* Logging framework and a log browser

See an [example notebook](https://github.com/cmutel/wurst/blob/master/docs/notebooks/marginal-mixes.ipynb) in the docs.

## License

BSD 2-clause license. Contributions are welcome!

## Authors

* Chris Mutel
* Brian Cox

## TODO

* Review BW2 IO code to make sure all needed fields are present in newly-created and modified databases
* Parameterized exchanges (e.g. electricity sector)
* Log browser web app

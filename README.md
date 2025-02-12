<!-- These are examples of badges you might want to add to your README:
     please update the URLs accordingly

[![Built Status](https://api.cirrus-ci.com/github/<USER>/pymeteos.svg?branch=main)](https://cirrus-ci.com/github/<USER>/pymeteos)
[![ReadTheDocs](https://readthedocs.org/projects/pymeteos/badge/?version=latest)](https://pymeteos.readthedocs.io/en/stable/)
[![Coveralls](https://img.shields.io/coveralls/github/<USER>/pymeteos/main.svg)](https://coveralls.io/r/<USER>/pymeteos)
[![PyPI-Server](https://img.shields.io/pypi/v/pymeteos.svg)](https://pypi.org/project/pymeteos/)
[![Conda-Forge](https://img.shields.io/conda/vn/conda-forge/pymeteos.svg)](https://anaconda.org/conda-forge/pymeteos)
[![Monthly Downloads](https://pepy.tech/badge/pymeteos/month)](https://pepy.tech/project/pymeteos)
[![Twitter](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter)](https://twitter.com/pymeteos)
-->

[![Project generated with PyScaffold](https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold)](https://pyscaffold.org/)

# pymeteos

> Python package to retrieve weather data from live data APIs. Playground for climate nerds that is interesting with long-term and extreme events!

# Structure

The repository has the following structure:

     ├── AUTHORS.md
     ├── CHANGELOG.md		 			<- Keep track of the changes.
     ├── CONTRIBUTING.md 				<- Documentation for development.
     ├── docs 							<- documentation in md or rst
     ├── environment.yml 				<- environment file for the pymeteos package
     ├── LICENSE.txt 					<- license
     ├── pyproject.toml 					<- pyproject
     ├── README.md 						<- here
     ├── setup.cfg 						<- Declarative configuration of the project
     ├── setup.py 						<- Use `pip install -e .` to install for
                                             development or or create a distribution with `tox -e build`.
     ├── src
     │   ├── pymeteos 			          <- python package where the main funtionality goes
     │   │   ├── provider
     │   │   │   ├── default_provider.py     <- define what provider should do
     │   │   │   └── meteostat.py 			<- generic provider
     │   │   └── weather_monster.py 		<- process and converts to nc
     │   └── service 					<- service module
     │       ├── config.toml 				<- config
     │       └── service.py 			     <- sercive
     ├── tests 						<- unit test
     └── tox.ini 					     <- Tox configuration file

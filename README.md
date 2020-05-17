# Fakegermano's Cookiecutter for Python Projects
A basic model of [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) for python projects containing some dependencies most of my python projects have.
Inspired by [fbidu's cookie-py](https://github.com/fbidu/cookie-py/)

## Usage
- Install [Poetry](https://python-poetry.org/docs/#osx-linux-bashonwindows-install-instructions)
- Install [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html)
- Run `cookiecutter gh:fakegermano/pycookie`

## Main dependencies and rationale
- `poetry`
To manage this dependencies in a reasonable way
- `pytest`
To have reasonable testing environments in every python project
- `pylint`
To avoid writing ugly/wrong code
- `black`
To make every python code uniform
- `ipython`
To have a python interpreter for the project that doesn't suck

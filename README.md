# MDID Documentation
==================

Experimental re-do of the docs with sphinx

Clone this repo to a new directory so you don't overwrite the original mdid-docs


## Setup

1. Clone this repo to a new directory so you don't overwrite the original mdid-docs
2. Make a new virtualenv, e.g.  ```mkvirtualenv msph``` (if you have virtualenvwrapper) or ```virtualenv msph``` if you don't
3. ```workon msph```
4. ```pip install -r requirements.txt```
5. From the root mdid-docs directory ```sphinx-build -b html source build```
6. ```open build/index.html```




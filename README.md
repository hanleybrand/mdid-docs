# MDID Documentation


Experimental re-do of the docs with sphinx - I think it works pretty well.

It's probably easiest to clone this repo to a new directory so you don't overwrite the original mdid-docs.

#### Advantages

* doc-centric structure (even if the TOCtree construct can be frustrating if you want it to do anything but list all the pages)

* automatic index & easy glossary


## Setup

1. Clone this repo to a new directory so you don't overwrite the original mdid-docs
2. Make a new virtualenv, e.g.  ```mkvirtualenv msph``` (if you have virtualenvwrapper) or ```virtualenv msph``` if you don't
3. ```workon msph```
4. ```pip install -r requirements.txt```
5. From the root mdid-docs directory ```sphinx-build -b html source build```
6. ```open build/index.html```

## Quick notes on doc formatting

Sphinx takes a little getting used to, but it has some really nice features. The only thing that makes me queasy about it is how it handles tables - basically if you're not an emacs user (I'm not) it's easier to pass in raw html.




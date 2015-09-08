# MDID Documentation


Experimental re-do of the docs with sphinx - I think it works pretty well.

#### Advantages

* doc-centric structure (even if the TOCtree construct can be frustrating if you want it to do anything but list all the pages)

* automatic index & easy glossary


#### Cons

* It might be fair to say it's over-engineered for the purposes of documenting MDID.


### Some good sphinx resources

[openalea sphinx cheat sheet](http://openalea.gforge.inria.fr/doc/openalea/doc/_build/html/source/sphinx/rest_syntax.html#text-syntax-bold-italic-verbatim-and-special-characters)

[publish sphinx output to gh pages](http://datadesk.latimes.com/posts/2012/01/sphinx-on-github/)

[cheatsheet at http://thomas-cokelaer.info](http://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html)



### Specific Sphinx extensions in use

[spinx-prompt] (https://github.com/sbrunner/sphinx-prompt)


## Setup

1. Clone this repo to a new directory so you don't overwrite the original mdid-docs
2. Make a new virtualenv, e.g.  ```mkvirtualenv msph``` (if you have virtualenvwrapper) or ```virtualenv msph``` if you don't
3. ```workon msph```
4. ```pip install -r requirements.txt```
5. From the root mdid-docs directory ```sphinx-build -b html source build```
6. ```open build/index.html```

## Quick notes on doc formatting

Sphinx takes a little getting used to, but it has some really nice features. The only thing that makes me queasy about it is how it handles tables - basically if you're not an emacs user (I'm not) it's easier to pass in raw html.




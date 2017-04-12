# Introduction to Python for the Macke lab

This repository collects some materials for visitors and new members of the lab to get up to speed on basic Python, with a particular focus on the type of machine learning applications we use here.

## What you will find here

A series of Jupyter notebooks introducing Python and machine learning
  - Python 101: Super basic introduction to basic Python.
  - Data Analysis 101: An introduction to Numpy, Scipy and Matplotlib. If you have some basic programming experience, especially in Python, you should probably start here.
  - Python 102: Some slightly more advanced techniques that crop up in virtually every real application. (In progress.)
  - Machine Learning 101: [ **TODO** ] (Might be combined with Neural networks 101.)
  - Neural networks 101: [ **TODO** ]

## What you will need

Before getting started, you should install the following:

  - Numpy
  - Matplotlib
  - Jupyter
  
  
### Instructions for Linux

#### Installing with pip.
If this works, it's preferable.

    pip install --user numpy
    pip install --user scipy
    pip install --user matplotlib
    pip install --user jupyter


#### Installing from the package manager.
If you are on Ubuntu,

    apt-get install python3-scipy
    apt-get install python3-matplotlib  #(is this included in scipy?)
    #apt-get install (Jupyter?)


### Instructions for OS X

Anaconda? [ **TODO** ]

### Instructions for Windows

Anaconda [ **TODO** ]

## Acknowledgements

This set of materials was put together by relying heavily on similar works by
  - [Rick Muller](http://nbviewer.jupyter.org/gist/rpmuller/5920182#ii.-numpy-and-scipy)
  - [ **TODO** ]

## External references

Based on a list compiled by [Rick Muller](http://nbviewer.jupyter.org/gist/rpmuller/5920182#ii.-numpy-and-scipy)
[ **TODO** Check the links and update where necessary ]

### Learning Resources
* [Official Python Documentation](http://docs.python.org/2.7), including
    - [Python Tutorial](http://docs.python.org/2.7/tutorial)
    - [Python Language Reference](http://docs.python.org/2.7/reference)
* If you're interested in Python 3, the [Official Python 3 Docs are here](http://docs.python.org/3/).
* [IPython tutorial](http://ipython.org/ipython-doc/dev/interactive/tutorial.html).
* [Learn Python The Hard Way](http://learnpythonthehardway.org/book/)
* [Dive Into Python](http://www.diveintopython.net/), in particular if you're interested in Python 3.
* [Invent With Python](http://inventwithpython.com/), probably best for kids.
* [Python Functional Programming HOWTO](http://docs.python.org/2/howto/functional.html)
* [The Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/full-text/book/book.html), written in Scheme, a Lisp dialect, but one of the best books on computer programming ever written.
* [Generator Tricks for Systems Programmers](http://www.dabeaz.com/generators/) Beazley's slides on just what generators can do for you.
* [Python Module of the Week](http://pymotw.com/2/contents.html) is a series going through in-depth analysis of the Python standard library in a very easy to understand way.

### Badass IPython Notebooks
* Rob Johansson's [excellent notebooks](http://jrjohansson.github.io/), including [Scientific Computing with Python](https://github.com/jrjohansson/scientific-python-lectures) and [Computational Quantum Physics with QuTiP](https://github.com/jrjohansson/qutip-lectures) lectures;
* [XKCD style graphs in matplotlib](http://nbviewer.ipython.org/url/jakevdp.github.com/downloads/notebooks/XKCD_plots.ipynb);
* [A collection of Notebooks for using IPython effectively](https://github.com/ipython/ipython/tree/master/examples/notebooks#a-collection-of-notebooks-for-using-ipython-effectively)
* [A gallery of interesting IPython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
* [Cross-disciplinary computational analysis IPython Notebooks From Hadoop World 2012](https://github.com/invisibleroads/crosscompute-tutorials)
* [Quantites](http://nbviewer.ipython.org/urls/raw.github.com/tbekolay/pyconca2012/master/QuantitiesTutorial.ipynb) Units in Python.
    - [Another units module is here](http://www.southampton.ac.uk/~fangohr/blog/)

### Packages for Scientists
Important libraries

* [Python](http://www.python.org) version 3.x (whatever 'x' currently is);
* [Numpy](http://www.numpy.org), the core numerical extensions for linear algebra and multidimensional arrays;
* [Scipy](http://www.scipy.org), additional libraries for scientific programming;
* [Matplotlib](http://matplotlib.sf.net), excellent plotting and graphing libraries;
* [IPython](http://ipython.org), with the additional libraries required for the notebook interface.
* [Sympy](http://sympy.org), symbolic math in Python
* [Pandas](http://pandas.pydata.org/) library for big data in Python

Other packages of interest
[ **TODO** Add ML packages here ]
* 
* 
* 


### Cool Stuff
* [Moin Moin](http://moinmo.in/), a wiki written in Python
* [Project Euler](http://projecteuler.net/), programming problems that would (?) have interested Euler. Python is one of the most commonly used languages there.

# Introduction to Python for the Macke lab

This repository collects some materials for visitors and new members of the lab to get up to speed on basic Python, with a particular focus on the type of machine learning applications we use here.

## What you will find here

A series of Jupyter notebooks introducing Python and machine learning
  - Python 101: Super basic introduction to Python.
  - Data Analysis 101: An introduction to Numpy, Scipy and Matplotlib. If you have some basic programming experience, especially in Python, you should probably start here.
  - Python 102: Some slightly more advanced techniques that crop up in virtually every real application. (In progress.)
  - Regression - Orientation tuning: An introduction to least-squares fitting, using orientation tuning as an example.
  - Machine Learning 101: [ **TODO** ] (Might be combined with Neural networks 101.)
  - Neural Networks 101: A practical introduction to neural networks for classification. In this tutorial you build a 3-layer neural network, and experiment with different sizes for the hidden layer.

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
    pip install --user scikit-learn


#### Installing from the package manager.
If you are on Ubuntu,

    apt-get install python3-scipy
    apt-get install python3-matplotlib  #(is this included in scipy?)
    #apt-get install (Jupyter?)
    pip install --user scikit-learn


### Installing using Anaconda
It's also possible to install the Anaconda distributing, which includes everything you need (Python + all the packages mentioned above). The package versions in Anaconda tend to lag a little behind since they do their own packaging, but as long as you don't need the absolute newest versions, this is perfectly fine. Follow the instructions from here: https://docs.continuum.io/anaconda/install-linux.html.

### Instructions for OS X

For the most pain-free installation, go with the Anaconda distribution. The installation instructions are here: [https://docs.continuum.io/anaconda/install-macos.html](https://docs.continuum.io/anaconda/install-macos.html).

You can also install through [Homebrew](https://www.scipy.org/install.html#homebrew), if you need the most recent versions.

### Instructions for Windows

Compiling your own software is notoriously non-trivial on Windows, so unless you have a good reason not to, go with the Anaconda. Instructions are found here: [https://docs.continuum.io/anaconda/install-windows.html](https://docs.continuum.io/anaconda/install-windows.html).

### After installing Anaconda

After installing Anaconda, you may want to install [scikit-learn](http://scikit-learn.org) package to run some of the examples in the [Data Analysis 101](Data%20Analysis%20101.ipynb).

    conda install scikit-learn

## Acknowledgements

This set of materials was put together by relying heavily on similar works by
  - [Rick Muller](http://nbviewer.jupyter.org/gist/rpmuller/5920182#ii.-numpy-and-scipy)
  - [Denny Britz](https://github.com/dennybritz/nn-from-scratch/blob/master/nn-from-scratch.ipynb)

## External references

Based on a list compiled by [Rick Muller](http://nbviewer.jupyter.org/gist/rpmuller/5920182#ii.-numpy-and-scipy)

### Learning Resources
* [Official Python Documentation](http://docs.python.org/3), including
    - [Python Tutorial](http://docs.python.org/3/tutorial)
    - [Python Language Reference](http://docs.python.org/3/reference)
* [IPython tutorial](http://ipython.org/ipython-doc/dev/interactive/tutorial.html).
* [Learn Python The Hard Way](http://learnpythonthehardway.org/book/).
  If you want to invest the time to learn good all-around programming in Python, and not just writing quick data analysis scripts, this is one of the best resources.
* [How to Think Like a Computer Scientist: Learning with Python](http://openbookproject.net/thinkcs/) A more classic text for learning Python. Make sure to read the Python 3 version.
* [Python Module of the Week](http://pymotw.com/3/) is a series going through in-depth analysis of the Python standard library in a very easy to understand way.
* [Invent With Python](http://inventwithpython.com/), probably best for kids.
* [Python Functional Programming HOWTO](http://docs.python.org/3/howto/functional.html)
* [The Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/full-text/book/book.html), will deepen your understanding of general programming principles. There is no Python in this book (the examples are written in Scheme, a Lisp dialect).

### Badass IPython Notebooks
* [A gallery of interesting IPython Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
* Each chapter of Rob Johansson's [Numerical Python](http://jrjohansson.github.io/numericalpython.html) can be downloaded as a notebook. Note that these use Python 2.
* [XKCD style graphs in matplotlib](http://nbviewer.ipython.org/url/jakevdp.github.com/downloads/notebooks/XKCD_plots.ipynb);

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
* [Project Euler](http://projecteuler.net/), programming problems that would (?) have interested Euler. Python is one of the most commonly used languages there.

Introduction to predictive analytics with pandas and scikit-learn
=================================================================

This repository contains notebooks to get started with predictive
analytics using scikit-learn and pandas.

This material is strongly inspired from the
[EuroPython 2014 scikit-learn tutorial](https://github.com/GaelVaroquaux/sklearn_pandas_tutorial)

* Olivier Grisel [@ogrisel](https://twitter.com/ogrisel) |
  http://ogrisel.com 

* Gael Varoquaux [@GaelVaroquaux](https://twitter.com/GaelVaroquaux) |
  http://gael-varoquaux.info

which was inspired by http://github.com/jakevdp/sklearn_scipy2013
by Jake VanderPlas [@jakevdp](https://twitter.com/jakevdp) | http://jakevdp.github.com

Installation Notes
------------------

This tutorial will require recent installations of *numpy*, *scipy*,
*matplotlib*, *scikit-learn*, *pandas* and *Pillow* (or PIL).

For users who do not yet have these packages installed, a relatively
painless way to install all the requirements is to use a package such as
[Anaconda](http://continuum.io/downloads), which can be downloaded and
installed for free.

Please download in advance the Olivetti dataset using:

    from sklearn import datasets
    datasets.fetch_olivetti_faces()


### With the IPython/jupyter notebook

The recommended way to access the materials is to execute them in the
IPython/jupyter notebook. If you have the notebook installed, you should
download the materials (see below), go the the `notebooks` directory, and
launch IPython notebook from there by typing:

    cd notebooks
    jupyter notebook  # ipython notebook if old version

in your terminal window. This will open a notebook panel load in your web
browser.

Downloading the Tutorial Materials
----------------------------------

I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file. I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.

Data Downloads
--------------

The data for this tutorial is not included in the repository. We will be
using several data sets during the tutorial: most are built-in to
scikit-learn, which includes code which automatically downloads and
caches these data. Because the wireless network at conferences can often
be spotty, it would be a good idea to download these data sets before
arriving at the conference. You can do so by using the `fetch_data.py`
included in the tutorial materials.

You will also need:

https://dl.dropboxusercontent.com/u/5743203/data/titanic/titanic_train.csv

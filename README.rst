Estimating classifier performance with only positive and unlabeled data
=========================================================================

This repository contains code accompanying our manuscript about estimating classifier performance with only positive and unlabeled data. 
A possibly outdated version of the manuscript is available at arXiv at http://arxiv.org/abs/1504.06837.

All logic is implemented in `semisup-metrics.py`. The accompanying notebooks (`performance-curves.ipynb` and `known-pos-vs-known-neg.ipynb`) implement
the use cases we reported in the manuscript and can serve as an API reference for the code. To open notebooks, make sure you have IPython
installed and the following command within this project’s root directory::

    ipython notebook

To run all code, you will need the following Python libraries:

- scipy.stats
- numpy
- optunity
- matplotlib

When checking out the code in Windows it is possible, depending on your git settings, that data.pkl will need its line endings changed.
This can be done by using a tool such as dos2unix.

This code was developed by Marc Claesen while at the STADIUS lab of KU Leuven, Dept. of Electrical Engineering. If this code is useful,
please cite the accompanying paper.

# Reproducible Experiment Platform (REP)

__REP__ is ipython-based environment for conducting data-driven research in a consistent and reproducible way.

Main include:

  * unified python wrapper for different ML libraries (wrappers follow __scikit-learn__ interface)
    * TMVA
    * Sklearn
    * XGBoost
    * uBoost
    * Theanets
    * Pybrain
    * Neurolab
  * parallel training of classifiers on cluster 
  * classification/regression reports with plots
  * interactive plots supported
  * smart grid-search algorithms with parallelized execution
  * versioning of research using git
  * pluggable quality metrics for classification
  * meta-algorithm design (aka 'rep-lego')


### Running using docker
We provide the docker container with __REP__ and all it's dependencies <br />
https://github.com/yandex/rep/wiki/Running-REP-using-Docker/

### Installation
However, if you want to install __REP__ on your machine, follow this manual:  <br />
https://github.com/yandex/rep/wiki/Installing-manually <br />
and https://github.com/yandex/rep/wiki/Running-manually

### Howto examples

To get started, look at the notebooks in /howto/  <br />
Notebooks in repository can be viewed (not executed) online at nbviewer: http://nbviewer.ipython.org/github/yandex/rep/tree/master/howto/  <br />
There are basic introductory notebooks (about python, IPython) and more advanced ones (about the REP itself)

### License
Apache 2.0, library is open-source.

### Bugtracker
https://github.com/yandex/rep/issues



A 2-days tutorial on how to analyze LSST-stack output data using python.

Outline
=======

Introduction
------------

- Short reminder about Python
- What is the LSST stack, and what is it for
- What tools will we be using today


The LSST stack
--------------

How to install and setup the LSST stack
```````````````````````````````````````

- Stable version and weeklies
- Setup of stack-install packages
- Install and setup of a non-stack packages

Overview of the data processing
```````````````````````````````

- My input data, and what `obs_*` should I be using
- Tasks and command line tools
- A complete data reprocessing work-flow
- What catalogs are produced and from which step of the pipeline

Access the data
```````````````

- What is a data dataIds - an example with CFHT data
- Get and open images
- Get and load catalogs
- First step to analysis


Python libraries for data analysis
----------------------------------

Overview of useful python libraries: a non-exausthive list
``````````````````````````````````````````````````````````

- useful native functionalities
- `numpy`
- `scipy`
- `math`
- `pandas`
- `matplotlib`, `seaborn`
- `astropy`
- `astroquery`
- `pyfits`, `h5py`
- `yaml`, `json`, `(c)Pickle`
- `healpy`

In more details
```````````````

- `numpy`
- `astropy`
- `scipy`
- `matplotlib`
- `other`


Build a python package for data analysis
----------------------------------------

Short tutotial to build a python package
````````````````````````````````````````

- setup.py
- pypy
- libraries
- notebooks
- install and test your code localy
 

Share your work and make it useful
``````````````````````````````````

- `git` / github: basic functionnalities
- continuous integration: Travis-CI
- documentation: `sphinx` and readthedoc
- static code analysis (how well my code is written): landscape
- "dynamic" code analysis (make and run my unit/integration tests): codecov

Conclusion
----------

TBD


Requirements
============

Install
-------

- Python 3 (conda install is the easiest way)
- Python libraries from the requirements.txt
- `git` + a github account

Knowledge
---------

  - install python - a lot of way to do that, and that could be a mess
  - install a python package
  - ipython
  - jupyter notebook
  - basis knowledge on python

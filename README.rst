LSST data release production (drp) analysis
===========================================

- **Purpose**: A 2-days tutorial on how to analyze LSST-stack output data using python
- **For**: Someone who wants to use the LSSt stack output and start analyzing it with Python
- **Where**: CC-IN2P3, Lyon, France
- **When**: Octobre 3-4, 2017


Outline
=======

1 Introduction
------------

- Short reminder about Python
- What is the LSST stack, and what is it for
- What tools will we be using today


2 The LSST stack
--------------

2.1 How to install and setup the LSST stack
```````````````````````````````````````

- Stable version and weeklies
- Setup of stack-install packages
- Install and setup of a non-stack packages

2.2 Overview of the data processing
```````````````````````````````

- My input data, and what `obs_*` should I be using
- Tasks and command line tools
- A complete data reprocessing work-flow
- What catalogs are produced and from which step of the pipeline

2.3 Access the data
```````````````

- What is a data dataIds - an example with CFHT data
- Get and open images
- Get and load catalogs
- First step to analysis


3 Python libraries for data analysis
----------------------------------

3.1 Overview of useful python libraries: a non-exausthive list
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

3.2 In more details
```````````````

- `numpy`
- `astropy`
- `scipy`
- `matplotlib`
- `other`


4 Build a python package for data analysis
----------------------------------------

4.1 Short tutotial to build a python package
````````````````````````````````````````

- setup.py
- pypy
- libraries
- notebooks
- install and test your code localy
 

4.2 Share your work and make it useful
``````````````````````````````````

- `git` / github: basic functionnalities
- continuous integration: Travis-CI
- documentation: `sphinx` and readthedoc
- static code analysis (how well my code is written): landscape
- "dynamic" code analysis (make and run my unit/integration tests): codecov

5 Conclusion
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

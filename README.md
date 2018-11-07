# Repository of example scripts for the (AC)³ Project

In this repository, a number of example Jupyter notebooks are presented to access various Earth System Science datasets published within the
scope of the TR172 *Arctic Amplification: Climate Relevant Atmopsheric and Surface Processes and Feedback Mechanisms* [**(AC)³**](http://www.ac3-tr.de/)
The datasets need to be downloaded separately from **[PANGAEA](http://www.pangaea.de/): Data Publisher for Earth & Environmental Science** using the links provided in the respective notebooks.

------
## Dependencies

A working Python stack, including NumPy, Matplotlib, Jupyter.

If you choose to use one of the available Python Distributions (e.g. Anaconda) the following steps can be skipped.

To setup a virtual Python3 environment, *virtualenv* is needed.

A new virtual environment can then be created in folder *pyac3* using

```sh
> virtualenv -p python3 pyac3
```

After activation of the virtual environment using:

```sh
> source pyac3/bin/activate
```

Within the newly created environment, additionally needed Python packages can be installed using *pip*. Note that, depending on the notebook you
want to excecute, not all packages might be necessary:

```sh
> pip install cython
> pip install numpy
> pip install matplotlib
> pip install scipy
> pip install cartopy
> pip install jupyter
> pip install python-hdf4
> pip install netcdf4
```
------
## Starting a Jupyter Notebook server:

A Jupyter Notebook server can be started locally in the virtual environment using:

```sh
> source pyac3/bin/activate
> jupyter-notebook
```

The standard browser should pop up and the desired notebook file (*something.ipynb*) can be started by selecting it.



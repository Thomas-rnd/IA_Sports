# IA_Sports

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)

This repository contains the entire [IA Sports](http://shop.oreilly.com/product/0636920034919.do), in the form of Jupyter notebooks.

![cover image](Notebooks/Images/IA_Sports.png)

## How to use this Book

- Read the book in its entirety online at https://github.com/Thomas-rnd/IA_Sports

- Run the code using the Jupyter notebooks available in this repository's [Notebooks](Notebooks) directory.

- Launch executable versions of these notebooks using [Google Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)

## About

The book was written and tested with Python 3.9.13, though other Python versions should work in nearly all cases.

The book introduces tools to personalize runner's training. Among the tools proposed to assess the athlete’s “muscular fatique” the analysis of heart rate variability (HRV) provides an indirect evaluation of the settings of autonomic control of heart activity. HRV analysis is performed through assessment of time-domain indices, like RMSSD but also in the frequency-domain indices, likes LF/HF.

This project was conducted by 4 people at the [ENSC](https://ensc.bordeaux-inp.fr/fr)

We used core libraries essential for working with data in Python: particularly [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org), and related packages.

## Software

The code in the book was tested with Python 3.9.13, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

The packages we used to run the code in the book are listed in [requirements.txt](requirements.txt)
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``IA_Sports`` with Python 3.9.13 and all the required package versions, run the following:

```
$ conda create -n IA_Sports python=3.9.13 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.

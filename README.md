Data Science Course
==================

This repository aims for complement resources for learning data science with Python.

Getting started
---------------
I am recommending to use Visual Studio Code for consumes these materials since it is built-in Jupyter notebook and terminal. However, if you like to use terminal + jupyterlab server that is ok as well. Please follow these steps to setup the envinronment so you can play with the materials:

Start by installing [Anaconda](https://www.anaconda.com/products/distribution) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)), [git](https://git-scm.com/downloads), 

Next, clone this project by opening a terminal and typing the following commands (do not type the first `$` signs on each line, they just indicate that these are terminal commands):

    $ git clone https://github.com/rebekz/datascience_course.git
    $ cd datascience_course

Next, run the following commands:

    $ conda env create -f environment.yml
    $ conda activate bol_datascience_course
    $ python -m ipykernel install --user --name=bol_datascience_course

If you aren't use Visual Studio Code then you need to start Jupyter Lab to able open the ipynb notebook

    $ jupyter lab

References
--------
* [Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow (3rd edition)](https://homl.info/er3)

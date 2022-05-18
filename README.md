# Introduction to Python 

This repository contains the materials (datasets, code and slides) for the 1-day Introduction to Python course taught at Esade for the Executive Master students in Business Analytics.

<img src="presentation/image_github.png" alt="alt text" width=1000 height="whatever">

# Contents
- [Installation](#Installation)
- [Materials](#Materials)        

# Installation
## Clone repository
If you want to make use of all the materials, cloning the code to your local or downloading it would be the best. In order to do so:

    git clone git@github.com:pepebonet/Class_Python.git

## Install dependencies
We highly recommend to use a virtual environment to work with the code, as additional packages may need to be downloaded as you keep coding. To do so: 

`Create environment:`

    conda create --name python_intro python=3.8
    conda activate python_intro

From there the only packages that are needed are `pandas` and `numpy` for now and that jupyter notebooks can be run. 

# Materials

The lecture materials are divided into three main components. The slides that will support the presentation, the coding materials for the topics covered, and the dataset that we will use. 

- [Slides for the lecture](presentation/Class_python_EMIBA.pdf)
- Jupyter notebooks for the different topics covered:
    - [Python Basics](scripts/Python_Basics.ipynb)
    - [Introduction to Pandas](scripts/Introduction_to_Pandas.ipynb)
    - [Introduction to Numpy](scripts/Introduction_to_Numpy.ipynb)
- Dataset for credit scoring in two formats: 
    - [tsv format](datasets/Dataset_credit_scoring.tsv)
    - [Excel format](datasets/Dataset_credit_scoring.xlsx)



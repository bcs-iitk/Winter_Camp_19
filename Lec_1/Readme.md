# Lec 1: Intro, Anaconda, Jupyter Notebook, Google Colab, Python, Numpy, SciPy, Matplotlib

Please find the link to intro slide [here](https://docs.google.com/presentation/d/e/2PACX-1vSIq_h1cnvcRo5MTQi9Ron9t3p4HIFW8MwvX-WtpzOIbmtpUMzyHzwrvxsANdTpbvaxZADiX8NW51oW/pub?start=false&loop=false&delayms=3000).

## Setup your environment to work locally on Python

You will need Python on your local machine to work through this tutorial. I recommend using the [Anaconda distribution](https://www.anaconda.com/distribution/) to use python on your machine. Kindly follow the below steps to setup your machine:

**Install Anaconda:** Kindly follow the steps given at the link: [for windows here](https://docs.anaconda.com/anaconda/install/windows/) and [for linux here](https://docs.anaconda.com/anaconda/install/linux/). Make sure to install the Anaconda for python version 3.7

**Create a Virtual Environment:** I strongly suggests you to always work with using different environment setups for your different projects to manage their individual dependencies. So, create a separate environment for this workshop and other works related to **BCS Winter Camp '19'**.

### Creating Anaconda Virtual environment
* Open terminal in linux or Anaconda CMD in windows and run ```conda create --name bcs_iitk python=3.7 anaconda``` to create a virtual environment with name **bcs_iitk**
* To work inside this environment activate it before executing any python program, run ```conda activate bcs_iitk```
* Once, you are done with your work exit the environment by running ```conda deactivate```

## Workshop Contents
### Intro to Jupyter Notebook/ Google Colab
* Make a new directory ```mkdir bcs_iitk_winter_19```
* Change your directory ```cd bcs_iitk_winter_19```
* Run ```jupyter notebook``` in terminal (linux) or Anaconda CMD (windows)
* This will open a link in your browser where you will work with the jupyter notebooks.
* You can work with jupyter notebooks online as well open [Google Colab](https://colab.research.google.com)

### Tutorial on Python, SciPy, NumPy, Matplotlib
* Open this [Link](python_tutorial.ipynb) for python tutorial and this [Link](numpy_matplot_tutorial.ipynb) for NumPy and Matplotlib tutorial.

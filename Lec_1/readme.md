# Lec 1: Intro, Anaconda, Jupyter Notebook, Google Colab, Python, Numpy, SciPy, Matplotlib

Please find the slide links [here](https://docs.google.com/presentation/d/e/2PACX-1vSIq_h1cnvcRo5MTQi9Ron9t3p4HIFW8MwvX-WtpzOIbmtpUMzyHzwrvxsANdTpbvaxZADiX8NW51oW/pub?start=false&loop=false&delayms=3000)

## Setup your environment to work locally on Python

You will need Python on your local machine to work through this tutorial. I recommend using the [Anaconda distribution](https://www.anaconda.com/distribution/) to use python on your machine. Kindly follow the below steps to setup your machine:

**Install Anaconda:** Kindly follow the steps given at the link: [1) for windows](https://docs.anaconda.com/anaconda/install/windows/) [2) for linux](https://docs.anaconda.com/anaconda/install/linux/). Make sure to install the Anaconda for python version 3.7

**Create a virtual environment:** I strongly suggests you to always work with using different environment setups for your different projects to manage their individual dependencies. So, create a separate environment for this workshop and other works related to **BCS**.

### Creating Anaconda Virtual environment

* Open terminal and run ```conda create --name bcs_iitk python=3.7 anaconda``` to create a virtual environment with name **bcs_iitk**
* To work inside this environment activate it before executing any python program, run ```conda activate bcs_iitk```
* Once, you are done with your work exit the environment by running ```conda deactivate```

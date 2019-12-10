# Python skills for research in Hydrology/Climate science

This repository contains a series of notebooks used in courses to introduce scientific Python to Hydrology students at the Vrije Universiteit Amsterdam. This series includes notebooks on basic Python skills, working with spatial data and time series analysis and has been created by Sem Vijverberg and Timothy Tiggeloven.

# Run

To run the notebooks **in the cloud** using Binder(https://mybinder.org) click on this badge:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/VU-IVM/Learning_Python.git/master)

# Install Python
To run the notebooks **locally** you need to have python installed. We strongly recommend to install Python rather sooner then later. The whole procedure should take around 15-20 minutes. To install Python, we advice to use a Minicoda(https://docs.conda.io/en/latest/miniconda.html) distribution. Install the Python 3.7 64 bit for your OS (MACOSX or Windows). 
When opening your terminal, you can now use 'conda' functionality manage your Python installation (creating environments and installing packages). 

- Mac has a terminal by default, you can open via spotlight (cmd+space) and then type terminal, press enter. 
- For Windows installing miniconda will come with a small programm called Anaconda promt. In this prompt you are able to use the conda commands.

Next, open the terminal and create a new conda environment. The environment_local.yml (likely) contains the packages that you will need for all the tutorials and practicums that you will do during your studies. After you installed anaconda, type the following in you terminal
`conda env create -f environment_local.yml`. 

We have named the environment 'hydrology'. Activate the conda environment by typing:
'conda activate hydrology'

After installation, download the repository from Github, open the terminal and go to the folder that you downloaded, then type (and wait a few seconds, the notebook will launch in your internet browser):
'jupyter notebook'

If you want to know more about how to install or update packages, you can take a look at the following site: https://www.marsja.se/learn-all-about-installing-updating-packages-in-python/



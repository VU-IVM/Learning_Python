# Python skills for research in Hydrology/Climate science

This repository contains a series of notebooks used in courses to introduce scientific Python to Hydrology students at the Vrije Universiteit Amsterdam. This series includes notebooks on basic Python skills, working with spatial data and time series analysis and has been created by Sem Vijverberg and Timothy Tiggeloven. For more information on the basics of Python, see this [Youtube channel](https://www.youtube.com/playlist?list=PL2fCZiDqOYYWvJSoIV9J3n-hlZIEoKEdu). In this Repo, the .ipynb files that start with a 0 concern the basics of Python. 


# Run via Binder

To run the notebooks **in the cloud** using Binder (https://mybinder.org) click on this badge:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/VU-IVM/Learning_Python.git/master)

# Run via Google Colab

1. Click on the green button Code and download the files: via *Download zip* or *git clone https://github.com/VU-IVM/Learning_Python.git*
2. Go to [Google Drive](https://drive.google.com/?utm_source=nl&utm_medium=button&utm_campaign=web&utm_content=gotodrive&utm_term=appspagecarousel&usp=apps_start&urp=https%3A%2F%2Fwww.google.com%2F). Note you can login with your VU account.
3. Unzip the Learning Python folder on your computer and drag the entire folder into your Google Drive.
4. Go to the folder Learning_Python and double click on the notebook (.ipynb file) you want to start. *Only the basics will run immediately on Google Colab, for other notebooks dependencies should be installed within a cell with !pip install dependency*
5. Now click on Open With
6. Now click on Connect more apps
7. Search for Colaboratory and install the app.
8. Now you can open the notebook with Google Colaboratory and start the assignment!

# Install Python on local computer

First, python needs to be installed and we will use Miniconda to manage our package dependencies.
To look at a tutorial video of the steps described below, click on the link here: https://video.vu.nl/media/1_wdgv3zl8 (the video explains the procedure only for a windows computer system).
To run the notebooks locally you need to have python installed. We strongly recommend to install Python sooner then later. The whole procedure should take around 15-20 minutes. To install Python, we advice to use a Miniconda (https://docs.conda.io/en/latest/miniconda.html) distribution. We need the Python 3.8 version, so you’ll have to scroll down to the older versions of the installer.

- For windows download Python 3.8 Miniconda3 Windows 64-bit
- For macOS download Python 3.8 Miniconda3 macOS Intel / Apple M1 ARM 64-bit pkg (not bash!). If you need Intel or Apple M1 ARM depends on the chip. Newer laptops will have an Apple M1 chip. You can check which chip is used by your laptop by clicking on the apple logo in the top left of the screen > About this Mac. Under chip it says either M1 or Intel.

When opening your terminal, you can now use 'conda' functionality manage your Python installation (creating environments and installing packages). 

- Mac has a terminal by default, you can open via spotlight (cmd+space) and then type terminal, press enter. 
- For Windows installing miniconda will come with a small programm called Anaconda prompt. In this prompt you are able to use the conda commands.

Next you need to create a new conda environment that contains the required packages for all the tutorials and practicums that you will do during your studies. For this purpose you need to download the 'environment.yml' file that can be found in the github. Move this file into the directory where you want to make the new environment.
Then open the terminal (if it’s not yet) and navigate to the directory where you placed the .yml file: check in which folder you are in the terminal by running ´ls´, then you can move one directory by using ´cd [directory_name] ´. To move up one directory use ´cd .. ´ (make sure your folder names do not have spaces, always use underscores).
If you are in the right directory, type the following in your terminalL 

`conda env create -f environment.yml`

We have named the environment 'hydromaster'. After creating the new environment, activate it by typing: 

`conda activate hydromaster` 

Depending on your internet connection, this can take quite some time. After installation, download the repository from Github or the practicum documents, open the terminal and go to the folder that you downloaded, then type (and wait a few seconds, the notebook will launch in your default internet browser): ´jupyter lab´. Next, to use the variable inspector extension for Jupyter Lab, right-click on cells (open variable inspector) and visually explore variables.

If you want to know more about how to install or update packages, you can take a look at the following site: https://www.marsja.se/learn-all-about-installing-updating-packages-in-python/
Additional notes: To open other user interface (such as spyder for example), the procedure is the same as for the jupyter lab, except that you have to type spyder.

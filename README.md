# ma2823_2017

This repository holds the computer labs for the MA2823 course (Introduction to Machine Learning) at CentraleSupelec in Fall 2017. The course website is at http://tinyurl.com/ma2823-2017 

## Getting the labs
Each lab is set up as a Jupyter notebook (.ipynb file). Although these will display in read mode when you click on them, you should download them locally to your computer in order to run and modify them. You can do this directly from the webpage, but we recommend forking then cloning the repository. If you are new to git and GitHub, you will find detailed instructions in the [syllabus](http://cazencott.info/dotclear/public/lectures/ma2823_2017/syllabus.pdf). 

## Setting up your computer
The labs require Python2.7 (Python 3.3 is fine as well, but you might encounter some minor issues with e.g. print statements). All required packages are part of the [Anaconda platform](https://www.anaconda.com/download/) so you can simply install Anaconda on your machine.

If you'd rather install just the required packages with pip, that is also possible. You will need:
* numpy and scipy https://www.scipy.org/install.html
* jupyter http://jupyter.org/install.html 
* matplotlib http://matplotlib.org/users/installing.html
* seaborn http://seaborn.pydata.org/installing.html
* pandas http://pandas.pydata.org/getpandas.html
* scikit-learn http://scikit-learn.org/stable/install.html

To __check your installation__, try launching Jupyter (e.g. by typing `jupyter noteboook` in a shell), navigating to where you have downloaded/pulled the first lab (.ipynb file) and opening it. In that notebook (or in a python terminal), you should be able to run 
  ```python
  import sklearn
  import pandas
  import seaborn
  import matplotlib
  ```
  


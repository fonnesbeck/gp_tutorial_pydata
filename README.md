# An Introduction to Gaussian Processes in PyMC3

PyData San Luis 2017  
Thursday, November 16, 16:00

## Software requirements

This tutorial is based on **Python 3**. I cannot guarantee that the materials will work well with Python 2 or earlier, so ensure Python 3.5 or greater is installed on your system.

I recommend installing the [Anaconda](https://www.continuum.io/downloads) distribution of Python 3, as it allows for the easy automation of package installation and virtual environment creation (see instructions below).

## Getting the tutorial materials

Clone this repository into a directory of your choice.

    git clone https://github.com/fonnesbeck/gp_tutorial_pydata.git

If you are not familiar with Git and GitHub, you can simply download the zip file of the repository at the top of the main repository page.

Then, move to the directory created by the clone/zip file:

    cd gp_tutorial_pydata

and install everything using `conda`:

    conda env create -f environment.yml

This will create an **environment** called `gp_tutorial` that includes the packages required for the course.    

If you are not using the Anaconda Python distribution, you will need to manually install the packages listed in `environment.yml` using `pip`.

Which you probably don't want to do.

So [install Anaconda](https://www.continuum.io/downloads).

To use the environment, you may type:

    source activate gp_tutorial

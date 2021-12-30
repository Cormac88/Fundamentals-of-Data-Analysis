![Matplotlib](https://upload.wikimedia.org/wikipedia/en/thumb/5/56/Matplotlib_logo.svg/1280px-Matplotlib_logo.svg.png)

![CAO](https://upload.wikimedia.org/wikipedia/commons/5/51/Central_Applications_Office.png)

# Overview of the Pyplot Python Package and a Data Analysis of the CAO Webiste

This repository contains an overview of the `matplotlib.pyplot` Python package and also a concise overview on how to load CAO points information from the CAO website into a pandas data frame and an analysis of the CAO from the last few years using different data analysis techniques.

## Overview

### pyplot.ipynb

This notebook contains:
- A concise overview of the matplotlib.pyplot Python package.
- An in-depth explanation of three interesting plots from the matplotlib.pyplot Python package which are:

1. Histograms
2. Scatter Plots
3. Box Plots


### cao.ipynb

This notebook contains:
- An overview of how to load CAO points information from the CAO website into a pandas data frame.
- A detailed comparison of CAO points in 2019, 2020, and 2021 using the functionality in pandas.
- Plots and other visualisations to show the data analysis which are
    - Countplots
    - Pieplots
    - Barplots
    - Histograms

## Quick Steps

### nbviewer:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/Cormac88/Fundamentals-of-Data-Analysis/tree/main/)

### Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Cormac88/Fundamentals-of-Data-Analysis/HEAD)

## Install

### Installing Python and Jupyter Notebook

1. Python and jupyter lab are needed to run the `.ipynb` files in this repository.

1. Download `Python` from https://www.python.org/.

2. Type `pip install jupyterlab` and press enter.

3. Wait for jupyter to finish installing.

Please see the official [Installation of Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) page if you are having issues.

### Installing Ghostscript

Download and Install [Ghostscript](https://www.ghostscript.com/releases/gsdnld.html). Choose public license 64 bit.

### Installing Camelot

Install [Camelot](https://camelot-py.readthedocs.io/en/master/) using the command pip install `camelot-py[cv]` in the command prompt.

Please see the official [Installation of Camelot](https://camelot-py.readthedocs.io/en/master/user/install.html) page if you are having issues.

## Running the Code

### Running the Code

1. Change directory to the folder that contains the.ipynb file you wish to run.

2. Type `jupyter lab`.

3. Jupyter lab will open in your browser as a new tab. Keep the command prompt window open as it needs to stay running while Jupyter Notebook is active.

4. Click on the `.ipynb` file you wish to run.

5. Click on `Kernel` and then select `Restart Kernal and Run All Cells`.

6. When finished, close the tab in your browser and then press press 'ctrl + C' in the command prompt to end the session.

## Explore

### Pyplot.ipnb

Changing some of the parameters for the following in the `pyplot.ipynb` notebook will have some interesting effects:

1. In the Changing the Figure Size section, change `Y = np.sin(X)` to `Y = np.cos(X)`
2. In the Saving Figures section, change the seed parameter inside `rng = np.random.default_rng(99)` and re run the whole notebook to see different data on the Scatter Plots.
3. In the Scatter Plots section, change the `low` and `high` values of the integers.
4. In the Scatter Plots section and the Box Plots section, change the cmap parameter using the [cmap list](https://matplotlib.org/stable/tutorials/colors/colormaps.html).
5. In the Tilting the Figure sub-section of the 3D Scatter Plot section, change the `ax.view_init` parameter to see different angles on the 3D Scatter Plot

### cao.ipynb

I created a filter in the `Round 1 Analysis` and `Round 2 Analysis` to check any course of interest. All you need to do is change the `college_choice` object to filter the courses.

## Credits

### Pyplot.ipnb

I heavily relied on the following YouTube channels:

[Kimberly Fessel](https://www.youtube.com/channel/UCirb0k3PnuQnRjh8tTJHJuA)<br>
[Corey Schafer](https://www.youtube.com/c/Coreyms)<br>

### cao.ipynb

I heavily relied on the following on the [statology](www.statology.org) website.

## Contact

[Cormac Hennigan](mailto:G00398284@gmit.ie)
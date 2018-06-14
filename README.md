# CS 235 Project - NFL Predictions
## Author of this code: Dharti Tarapara

#### ALL CODE HAS BEEN DERIVED FROM A TUTORIAL ON SCIKIT-LEARN WRITTEN BY PIUSH VAISH, FOUND HERE:
#### http://adataanalyst.com/machine-learning/predicting-nba-winners-decision-trees-random-forests-scikit-learn/

Note: a sample subset of data was not included. The full dataset is the only one included. The reason for this is that accurate results cannot be obtained for the NFL prediction using just a year or two of data. That being said, the data is not large enough to cause major delays. The entirety of the program should finish outputting results in roughly 2 - 3 minutes maximum.

## Technology
Python

## To Run
This folder contains two python files:

nfl.py
NFL.ipynb

#### nfl.py
The first half of this file contains code written to build, train, and test the decision tree. This code is the same code as NFL.ipynb. However, all GraphViz- and Image-based code has been removed to make it compatible with a traditional Python environment. As a result, the file does not display the tree (the tree can instead be found in NFL.ipynb).
The second half of this file contains the code to test the resulting tree on new data (the upcoming NFL season). The outputs of this file include: accuracy measurements at various points throughout the code, and the resulting predicted Super Bowl 2018 champion.

A Makefile has been included to run this file. To run, simply type
'make'
into your terminal. This will run the command
'python nfl.py'
and output its results.

#### NFL.ipynb
This file contains all code written to build, train, and test the decision tree. The outputs of this file include: accuracy measurements at various points throughout the code, and the resulting tree diagram is depicted near the bottom of the file.

To view this file, open it using a Jupyter/IPython Notebook. The code is interactive and already displays the output.

## Data
The data files include all game data from 2013 - 2017 (2013to2017.csv), team ranks (rank.csv), and division teams (afcw.csv, afcs.csv, nfcn.csv, nfce.csv, ...).

The data files used have already been hard-coded into the files, so there is no need to pass them in as arguments.

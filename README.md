# Machine Learning - Predicting Boston Housing Prices

## Table of Contents
- [Overview](#Overview)
- [Dependencies](#Dependencies)
- [Code](#Code)
- [Running the code](#Running-the-code)
- [Data](#Data)

## Overview
In following project, we predict the selling price of a house in Boston, Massachusetts area using basing machine learning concepts. In order to perform prediction, data evaluation, model development, and model performance analyzation is done. For predicting model, DecisionTree Regressor is chosen in this project.

Project proceeds as follow:
- Data inspection and exploration
- Developing model
- Analyzing model performance
- Evaluating model performance

## Dependencies

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

## Code

- `boston_housing.ipynb` : Main file where all the works are performed
- `visuals.py` : Supplementary code for visualizing results
- `housing.csv` : Dataset for following project

## Running the code

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

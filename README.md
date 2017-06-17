# udacity-model-evaluation-and-validation
Model evaluation and validation project for Udacity's Machine Learning Nanodegree

### Requirements

* Language:- **Python 2.7**

    Python libraries:
    - [NumPy](http://www.numpy.org/)
    - [Pandas](http://pandas.pydata.org/)
    - [matplotlib](http://matplotlib.org/)
    - [scikit-learn](http://scikit-learn.org/stable/)

    Additional software:
    
    * [Jupyter Notebook](http://ipython.org/notebook.html) to run IPython notebooks.

### Code

The original template and supporting files are taken from ```projects/boston_housing``` folder of Udacity's  [machine-learning](https://github.com/udacity/machine-learning) repository on GitHub.

Review: [Model evaluation and validation rubric](https://review.udacity.com/#!/rubrics/103/view)


### Run

In a terminal or command window, navigate to the folder `boston_housing/` in project directory and run one of the following commands:

```bash
jupyter notebook boston_housing.ipynb
```
or
```bash
ipython notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

# MLND_capstone_project
### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

Template code is provided in the `Forecasts_Jewelry_1.66_initial.ipynb` notebook file and `Forecasts_Jewelry_1.66_5xData.ipynb` . You will also require `product_per_day.csv` and `product_per_day_moredata.csv` dataset files. 

### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
jupyter notebook Forecasts_Jewelry_1.66_initial.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The dataset consists of 50 data points for `product_per_day.csv` and 250 for `product_per_day_moredata.csv` with each datapoint referring to the amount of product sold per day at a given day from April to May 2018.

**Features**
- There are no features in this dataset, they are constructed within the jupyter notebook itself.

**Target Variable**
- `product grams`: quantity of grams sold of a single product line.

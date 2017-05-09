# restaurant-inspections
Data analysis on LIVES (restaurant inspection) data.

## Synopsis
A Jupyter notebook that can perform some analyis on the common restaurant inspection data format pioneered by Yelp.

## Installation

This assumes you've already installed Python3, Pandas, and Jupyter ([Jupyter-Notebook](http://jupyter.readthedocs.io/en/latest/install.html), or Jupyter-Lab).


``` sh
$ cd [your workspace]
$ git clone https://github.com/pubdata/restaurant-inspections.git
$ cd restaurant-inspections/notebooks
$ jupyter notebook
```

## Update to the latest data

``` sh
$ cd [your workspace]/restaurant-inspections
$ wget http://ehservices.publichealth.lacounty.gov/LIVES/LABusinesses.zip -O data/LABusinesses.zip
$ unzip -o -d data data/LABusinesses.zip
```


## Example

A read-only view of the notebook can be viewed from [the github repository](https://github.com/pubdata/restaurant-inspections/blob/master/notebooks/inspections.ipynb).

A [blog article](https://medium.com/@sgornick/practicing-data-analysis-on-restaurant-inspection-data-b5719fa49062) describes the analysis further.


## License

MIT

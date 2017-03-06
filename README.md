# BEEM
## NBA Prospect Projection System (Bagging Error Estimate using Meta-Features) Version 2

BEEM generates a linear regression primarily using box-score data, and then adjusts the estimates using bagging algorithm on the error with a combination of physical and athletic features as well as meta-features derived from box-score data.

## Results

Using scorer '[Draft Rank Value](http://www.tothemean.com/2015/07/26/how-to-compare-draft-rankings.html)' by Jesse Fischer, the following results are acheived.

![results](https://github.com/matthewignal/BEEM/blob/master/Drafted.png)

For an average draft rank value of 45.1.

# Updates

2/16/17: New linear feature, True Shooting percentage, improves DRV from 44.6 to 44.8

3/5/17: New linear feature, Height divided by positional average height, improves DRV from 44.8 to 45.1

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

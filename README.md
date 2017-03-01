# BEEM
## NBA Prospect Projection System (Bagging Error Estimate using Meta-Features) Version 1

BEEM generates a linear regression using a combination of box-score data and meta-features, and then adjusts the estimates based on error analysis by using these meta-features.

## Results

Using scorer '[Draft Rank Value](http://www.tothemean.com/2015/07/26/how-to-compare-draft-rankings.html)' by Jesse Fischer, the following results are acheived.

![results](https://github.com/matthewignal/BEEM/blob/master/Drafted.png)

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

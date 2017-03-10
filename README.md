# BEEM
## NBA Prospect Projection System (Bagging Error Estimate using Meta-Features) Version 2

## Summary

BEEM generates a linear regression primarily using box-score data, and then adjusts the estimates using bagging algorithm on the error with a combination of physical and athletic features as well as meta-features derived from box-score data.

I include standardized pre-draft statistics, beginning in 2003, from international play, national tournaments, and the NCAA. I use RealGM's database for box-score statistics, DraftExpress' pre-draft measurements and combine results, and hoop-math.com's play-by-play statistics for post-2012 NCAA prospects.

## Features

Linear Features: Age, points, true shooting %, rebounds, steals, blocks, free throw rate, assists, assist-to-turnover ratio, free throw percentage, fouls, and height divided by positional average height.

Bagging (on the error) Features: SpeedxAgility, No-StepxStep Vertical, height, wingspan to height ratio, weight to height ratio, outside shooting score, defense score, inside scoring score, playmaking score, free throw rate, and the linear prediction.

## Results

Using scorer '[Draft Rank Value](http://www.tothemean.com/2015/07/26/how-to-compare-draft-rankings.html)' by Jesse Fischer, the following results are acheived.

![results](https://github.com/matthewignal/BEEM/blob/master/Drafted.png)

For an average draft rank value of 45.1.

# Updates

2/16/17: New linear feature, True Shooting percentage, improves DRV from 44.6 to 44.8

3/5/17: New linear feature, Height divided by positional average height, improves DRV from 44.8 to 45.1

Next update (March 2017) will include NCAA conference statistics standardization and include 2016-2017 season.

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

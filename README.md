# surfs_up Analysis

## Overview of the analysis
On this analysis we help surfs_up to get information about temperature trends before opening the surf shop, we compare data from June and December from 2001 to 2007 in Oahu using the sqlalchemy library to read a sqlite local data base with jupyter notebook.

## Results

### June Temperatures Summary Table

![June_Temps](https://github.com/ggalguera/surfs_up/blob/main/June_Temperature_Summary.png)

### December Temperatures Summary Table

![December_Temps](https://github.com/ggalguera/surfs_up/blob/main/December_Temperature_Summary.png)

### Main Differences
During the analysis we detected evident differences on the month temperature
* The average Temperature for June is 74.94 degrees compared with 71.04 degrees for December, 3.9 degrees of difference that we can say is due to the season variation.
* The maximun Temperature is 85 degrees for June versus 83 degrees for December, for this case the variation is 2 degrees that shows that Oahu remain warm during the whole year.
* The minimun Temperature for June is 64 compared with 56 degrees in December, here is where we have the main difference, mainly caused by some chill nights over the winter.

## Summary

### Hihg Level Summary
Considering the Maximun and average temperatures of the two months we can conclude that Oahu remains warm for the whole year, the Standard Deviation for June is 3.26 compared with 3.75 in December this means it is pretty consistent and people would like to have an ice cream and practice some surf on eithe on June or December. I consider it is a good idea to open the Surf and Shake shop as we will have customers all year around.

### Aditional Queries
* And aditional query cold be to compare Year Over Year Temperatures and detecte any possible trend.
* We also can run a query by day average and then create a plot chart that visually compare the temperature behavior over the month.

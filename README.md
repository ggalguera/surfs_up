# surfs_up Analysis

## Overview of the analysis
On this analysis we help surfs_up to get information about temperature trends before opening the surf shop, we compare data from June and December from 2001 to 2007 in Oahu using the sqlalchemy library to read a sqlite local data base with jupyter notebook.

## Results

### Summary Table
June Temperatures Summary Table
![June_Temps](https://github.com/ggalguera/surfs_up/blob/main/June_Temperature_Summary.png)
December Temperatures Summary Table
![December_Temps](https://github.com/ggalguera/surfs_up/blob/main/December_Temperature_Summary.png)

### Main Differences
During the analysis we detected evident differences on the month temperature
* Average Temperature is 74.94 degrees for June compared with 71.04 degrees for December, 3.9 degrees of difference that does not represent a big variation.
* Maximun Temperature is 85 degrees for June versus 83 degrees for December, for this case the variation is only 2 degrees that shows that Oahu remain warm during the whole year.
* Minimun Temperature for June was 64 compared with 56 degrees in December, here is where we have the main difference, mainly caused by some chilli nights over the winter.

## Summary

### Hihg Level Summary
Considering the Maximun and average temperatures over the two months we can conclude that Oahu remains warm for the whole year, the Standard Deviation for June is 3.26 compared with 3.75 in December this means it is pretty consistent and people would like to have an ice cream either on June or December and practice some surf on either month.

### Aditional Queries
* And aditional query cold be to compare Year Over Year Temperatures and detecte any possible trend.
* We also can run a query by day average and then create a plot chart that visually compare the temperature behavior over the month.

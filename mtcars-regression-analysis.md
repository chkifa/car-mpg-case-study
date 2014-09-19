---
title: "Factor analysis of car miles per gallon (MPG)"
author: "Andre Balleyguier"
date: "September 2014"
output:
  pdf_document: default
  html_document:
    theme: cerulean
---

This document is my Course Project submission for the class "Regression Models" on Coursera.

# Summary

This study is an analysis of the very famous <mtcars dataset>(https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html), available in R. It aims at explaining the possible relationships between a car's miles per gallon measure, and the different other characteristics of the car. In particular, we will focus our attention on the transmission in order to give an answer to the two following questions:

* Is an automatic or manual transmission better for MPG?
* How can we quantify the MPG difference between automatic and manual transmissions?

First of all, we will explore the data to get a better overview of the underlying patterns in the dataset, and then we will build several linear models to explain and quantify the relationships between transmission and MPG.

# Analysis

## Data Exploration

### Loading data


```r
data(mtcars)
summary(mtcars)
```

```
##       mpg            cyl            disp             hp       
##  Min.   :10.4   Min.   :4.00   Min.   : 71.1   Min.   : 52.0  
##  1st Qu.:15.4   1st Qu.:4.00   1st Qu.:120.8   1st Qu.: 96.5  
##  Median :19.2   Median :6.00   Median :196.3   Median :123.0  
##  Mean   :20.1   Mean   :6.19   Mean   :230.7   Mean   :146.7  
##  3rd Qu.:22.8   3rd Qu.:8.00   3rd Qu.:326.0   3rd Qu.:180.0  
##  Max.   :33.9   Max.   :8.00   Max.   :472.0   Max.   :335.0  
##       drat            wt            qsec            vs       
##  Min.   :2.76   Min.   :1.51   Min.   :14.5   Min.   :0.000  
##  1st Qu.:3.08   1st Qu.:2.58   1st Qu.:16.9   1st Qu.:0.000  
##  Median :3.69   Median :3.33   Median :17.7   Median :0.000  
##  Mean   :3.60   Mean   :3.22   Mean   :17.8   Mean   :0.438  
##  3rd Qu.:3.92   3rd Qu.:3.61   3rd Qu.:18.9   3rd Qu.:1.000  
##  Max.   :4.93   Max.   :5.42   Max.   :22.9   Max.   :1.000  
##        am             gear           carb     
##  Min.   :0.000   Min.   :3.00   Min.   :1.00  
##  1st Qu.:0.000   1st Qu.:3.00   1st Qu.:2.00  
##  Median :0.000   Median :4.00   Median :2.00  
##  Mean   :0.406   Mean   :3.69   Mean   :2.81  
##  3rd Qu.:1.000   3rd Qu.:4.00   3rd Qu.:4.00  
##  Max.   :1.000   Max.   :5.00   Max.   :8.00
```

You can also embed plots, for example:


```
## Warning: NAs introduced by coercion
## Warning: no non-missing arguments to min; returning Inf
## Warning: no non-missing arguments to max; returning -Inf
```

```
## Error: need finite 'ylim' values
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## Simple model


## Further models and quantitative analysis

# Appendix

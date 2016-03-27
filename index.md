---
title       : Miles Per Gallon
author      : Lineesh Thamaran
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Miles Per Gallon

This presentation describes the Miles per gallon application


URL : https://lineesh.shinyapps.io/mtcars/


## Mileage analysis


This application allows the user to plot mpg against other parameters including Cylinders, Transmission, Gears and Weight.
Use the Variable radio button to select the parameter.


```r
head(mtcars)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

--- .class #id 

## mpg vs Cylinders 

The mpg vs Cylinder plot shows how the mpg varies for 4 Cylinders, 6 Cylinders and 8 Cylinders.


## mpg vs Transmission

The mpg vs Transmission plot shows how the mpg varies for Automatic and manual transmission.

--- .class #id 

## mpg vs Gears

The mpg vs Gear plot shows how the mpg varies for 3, 4 or 5 gears.

## mpg vs Weight 

The mpg vs Weight  plot shows how the mpg varies by weight of the car.

--- .class #id 

## Show outliers

Show outliers option allows the user to include or exclude the outliers.

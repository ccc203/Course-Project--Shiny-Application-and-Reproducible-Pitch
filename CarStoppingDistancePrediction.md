Course Project: Shiny Application and Reproducible Pitch
========================================================
author: Chunhui Chen
date: Tue Aug 23 17:23:12 2016
autosize: true

Course Project
========================================================

- This is the final presentation for the Course Project of the “Data Products” course
- The project has two tasks for the studenet:
  * Create a Shiny application
  * Create a presentation in Slidify or Rstudio Presenter to pitch for the application.
        

Stopping Distance Prediction Application: Dataset
========================================================
- For this assignment, we used the cars dataset from R package.
- The data give the speed of cars and the distances taken to stop. Note that the data were recorded in the 1920s.
- Some information about the dataset:

```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Stopping Distance Prediction Application: Model
========================================================
- We used lm to fit a linear model based on cars dataset.
- With this linear model, we can predict a car's stopping distance in meters based on the a given speed in miles per hour.
- This regression line is shown in blue with its 95% confidence interval.

![plot of chunk unnamed-chunk-2](CarStoppingDistancePrediction-figure/unnamed-chunk-2-1.png)


Stopping Distance Prediction Application
========================================================
- The application weblink can be found here [link](https://ccc203.shinyapps.io/CarBreakingDistancePredictor/).
- The underlying R codes can be found in this [Github](https://github.com/ccc203/Course-Project--Shiny-Application-and-Reproducible-Pitch) link.



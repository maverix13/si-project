# Statistical Inference Tooth Growth
maverix13  
September 27, 2015  

#Synopsis

This document analyzes the ToothGrowth data in the R datasets package. Following step are performed for statistical inference. 

1. Load the ToothGrowth data and perform some basic exploratory data analyses 
2. Provide a basic summary of the data.
3. Use confidence intervals to compare tooth growth by supp and dose.
4. State your conclusions and the assumptions needed for your conclusions. 

# Load Tooth Growth Data

```r
data("ToothGrowth")
summary(ToothGrowth)
```

```
##       len        supp         dose      
##  Min.   : 4.20   OJ:30   Min.   :0.500  
##  1st Qu.:13.07   VC:30   1st Qu.:0.500  
##  Median :19.25           Median :1.000  
##  Mean   :18.81           Mean   :1.167  
##  3rd Qu.:25.27           3rd Qu.:2.000  
##  Max.   :33.90           Max.   :2.000
```

# Exploratory Data Analysis

You can also embed plots, for example:

![](ToothGrowth_files/figure-html/unnamed-chunk-2-1.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

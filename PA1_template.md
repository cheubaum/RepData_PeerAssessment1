# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
activity <- read.csv("activity.csv")
no_na_activity <- activity[complete.cases(activity),]
```

## What is mean total number of steps taken per day?

```r
hist(no_na_activity$steps)
```

![](PA1_template_files/figure-html/unnamed-chunk-2-1.png) 

```r
mean(no_na_activity$steps)
```

```
## [1] 37.3826
```

```r
median(no_na_activity$steps)
```

```
## [1] 0
```

## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?

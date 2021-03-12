# VBA_Challenge

## Overview
The purpose of this worksheet was to analyze stock from multiple years.  The daily volume and yearly return rate where the performance points used to measure the stock's performance over different years.

## Purpose
The original code was refactored to improve efficiency in an effort reduce the run time.  This greater efficiency and shorter runtime will allow for analysis larger datasets in the future. 

## Results

### Refactored Changes
In the original code variables were used to hold the values used to calculate the yearly return rate.  These values where held in an array in the refactor code. By using arrays the routines can be separated into different loops reducing the time of loops take to complete.

### Runtime Analysis
By collecting the start time and end time of the code the runtime was able to be determined.

The original code produced runtimes of the following for the years 2017 and 2018 respectively.

![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/Original_2017.png) 
![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/Original_2018.png)

The refactor code produced the runtimes for following for the years 2017 and 2018 respectively.

![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/VBA_Challenge_2017.png) 
![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/VBA_Challenge_2018.png)

## Summary
There is always a need to reduced runtime to improve the performance of programs for the end user.  This should be the object of refactoring code and with each iteration of changes the performance should be monitored.  Some disadvantages of refactoring are that the amount of performance gained is insignificant or the original purpose of the code is corrupted resulting in a poorer experience for the end user. 

From the runtime results there is a significant reduction in the runtime from the original code.  With less lag time the code will be more versatile in the size of datasets analyzed and will make allow end users easier ability to analyze stocks.

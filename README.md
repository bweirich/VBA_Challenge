# VBA_Challenge

## Overview
The purpose of this worksheet was to analyse stock from multiple years.  The daily volume and yearly return rate where the performance points used to measure the stocks performance over different years.

## Purpose
The original code was refactored to improve effiecency in an effort reduce the run time.  This greater efficency and shorter runtime will allow for analysis a larger datasets in the future. 

## Results

### Refactored Changes
In the original code variables where used to hold the values used to calculate the yearly return rate.  These values where held in an array in the refactor code. By using arrays the routines can be separated into different loops reducing the time of loops take to complete.

### Runtime
By collecting the start time and end time of the code the runtime was able to be determined.

The original code produced runtimes of the following for the years 2017 and 2018 respectively.

![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/Original_2017.png) 
![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/Original_2018.png)

The refactor code produced the runtimes for following for the years 2017 and 2018 respectively.

![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/VBA_Challenge_2017.png) 
![alt_text](https://github.com/bweirich/VBA_Challenge/blob/main/VBA_Challenge_2018.png)

## Summary
From the runtime results there is a significant reduction in the runtime from the original code.  This will allow for the size of the dataset analysed to increase with less lag time making it more productive and will allow users easy access to the stock analysis results.

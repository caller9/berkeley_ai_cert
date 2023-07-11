# Module 5 Assignment 5.1 - Driver Coupon Acceptance

## Summary

This repository contains an analysis of data supplied by the UCI Machine Learning repository with Amazon Mechanical Turk survey data about the acceptance of a coupon by a driver presented with several scenarios.

* A coupon to a bar, restaurant under $20, restaurant from $20-$50, coffee house, or carry-out restaurant.
* Drivers provided various attributes about their direction of travel relative to the coupon, their final destination, and how frequently they visited each type of establishment
* Drivers also supplied information about gender, parenthood, education, occupation, weather, time of day, and passengers in their car.

## Analysis

The [Jupyter notebook](report.ipynb) contains the data analysis and recommendations. The notebook takes into consideration the effect of demographics, destination, coupon travel duration and direction, previous visit frequency, passengers, expiration time, and time of day. 

The end of the report concludes that the strongest influences on the acceptance of the coupon are the type of coupon and the frequency with which the driver visits that type of establishment. The time of day, expiration time, passengers in the vehicle, direction of travel, and duration of travel relative to their destination each play a role as well. 

Having more information about the driver's habits and current situation help you to offer the best coupon type and location.

The repository also contains the [Prompt](prompt.ipynb) notebook with some introductory examination prompted by the course.
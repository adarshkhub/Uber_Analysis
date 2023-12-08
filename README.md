# Uber_EDA_Analysis
Analysis done using Pandas, Matplotlib, Numpy, Seaborn
## Overview
Having previously done an EDA on feaux uber data "pyber" I was curious about how the process would feel with some real data. This is an Uber data set from Kaggle showing a customer's uber usage behavior over the course of a year. 

## Results

####Cleaning the data set
![Drop Extra Columns Boston](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/a50b4fd0-a1c4-434d-9d1a-7fd83c86fff5)
![dropna](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/8f5b6e4a-eb42-4d35-9ac6-77291a4c2e36)
![String as DateTime](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/5d3d4bed-a9eb-4da8-b31f-7b20bfa665b9)

#### We see most trips were taken as business expenses
![Uber Category Bar Chart](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/f8996d0a-3413-4237-9cb4-603d1279c7bd)
#### Meetings and Meals/Entertainment were most often the reason for booking uber rides
![Uber Purpose Bar Chart](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/6223ee61-550b-40ef-936b-e96800bfc025)

#### Interestingly when looking at data from two different uber locations there was no correlation in which day was most frequently used for Uber rides, I would have guessed Friday to be a trend
![Trips vs Days Boston Chart](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/81239215-4333-46c1-9e8f-81d191acfd1d)
![Trips vs Days NonBoston Chart](https://github.com/adarshkhub/Uber_Analysis/assets/67844710/92fd2ae4-5110-4d36-9233-00d017719ff5)



## Summary

Cleaning real data posed slightly more challenges then test data. It was interesting to see how many different columns of data were present in the second data set, most of which I didn't choose to use for eda. In the future I would try to pull data on drivers rather than passenger behavior as I feel stronger insights can be derived from seeing the behavior of many different passengers rather than an case study of one passenger.

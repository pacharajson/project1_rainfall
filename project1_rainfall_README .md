# Project 1: Exploring Climate Data of Singapore

## Problem Statement
Food delivery app has faced big issue about severe rainfall over years. This report got from operation team which would help data science team to set question and analyze related data given from operation team. After the analyzed had done, this will gear toward to these audience group: operation team, marketing team, managing team, and other related team to understand Singapore's rainfall. These problems define in this following:
> 1. Facing high demand of users when rainfall, lead to cancel from messengers (riders)
> 2. Rarely to find riders to pick up food
> 3. Food delivery app would like to increase food order amount and sales

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|total_rainfall|float|rainfall-monthly-total|Total rainfall in mm|
|month|datetime64|YYYY-MM-DD|Show date|
|no_of_rainy_days|int|how many times rainy a day|Number of rainfall per day|
|maximum_rainfall_in_a_day|float|max-of-rainfall-rate|Show maximum rainfall rate|
|mean_rh|float|mean-of-relative-humidity|Show mean of relative humidity|
|mean_sunshine_hrs|float|mean-of-sunshine-per-hours|Show mean of sunshine per hours|
|num_month|int|month-number|month_number eg. Feb=2, Sep=9

## Brief Analysis

### Boxplot each features
![Boxplot Total Rainfall](https://github.com/pacharajson/project1_rainfall/blob/main/Boxplot%20Total%20Rainfall.png)
![Boxplot Number of Rainy Days](https://github.com/pacharajson/project1_rainfall/blob/main/Boxplot%20Number%20of%20Rainy%20Days.png)
![Boxplot Mean of Relative Humidity](https://github.com/pacharajson/project1_rainfall/blob/main/Boxplot%20Mean%20of%20Relative%20Humidity.png)
![Boxplot Mean of Sunshine per Hour](https://github.com/pacharajson/project1_rainfall/blob/main/Boxplot%20Mean%20of%20Sunshine%20per%20Hour.png)
To check outliers and correlation in each features


### Exploratory Data Analysis
![Total_rainfall_high_rainfall_month](https://github.com/pacharajson/project1_rainfall/blob/main/total_rainfall_high_rainfall_month.PNG)
This figure shows that relationship between total rainfall and highest rainfall by month has positive relationship.
It can estimate that the volume of rainfall which month is highest and frequency of rainfall. The lowest rainfall is June (drizzle) and it is going to heavier rainfall til December and then it is going to decrease on January.

![Number_Rainy_Days_Month](https://github.com/pacharajson/project1_rainfall/blob/main/Number_Rainy_Days_Month.PNG)
Comparing with previous figure, it is not quite similar. This figure shows number of rainy days by month and calculating by mean of rainy days. The lowest number of rainy days is February which is approximately 8 days. In the opposite, the highest rainy days is November follow by December which are about 17.5 days.

![mean_rh_rainfall](https://github.com/pacharajson/project1_rainfall/blob/main/mean_rh_rainfall.PNG)
This scatterplot shows that these two features have relationship and shows the curve when mean of relative humidity trend is going to increase by month. The total rainfall is increase as well. Plus, the density of month 12 is navy that means it can be related to previous figures that mentioned.

![no_rainy_days_mean_sunshine](https://github.com/pacharajson/project1_rainfall/blob/main/no_rainydays_mean_sunshine.PNG)
Second, scatterplot shows mean of sunshine per hour compare with number of rainy days. If sunshine is going to decrease hours, it is highly possible to be rainy days. Moreover, it is related to number of rainfall figures which shows the highest rainfall on February which possible sunshine day (approximate mean of rainfall for 8 hours) and December has almost rainfall everyday.

![total_rainfall_rainy_days](https://github.com/pacharajson/project1_rainfall/blob/main/total_rainfall_rainy_days.PNG)
Lastly, the correlation between total rainfall and number of rainy days have a positive relation. That's mean volume of rainfall is increasing and number of rainy days is going to increase as well. Plus, this figure compare with first two figures are related because December is the highest total rainfall and number of rainy days.


## Conclusions and Recommendations
In conclusion, rainfall in Singapore almost happen over year. To apply with problem statement about the business in this following:
> 1. How to control high demand of users during rainfall
> 2. How to increase attention to work during rainfall for riders
> 3. Cancellation by riders and customers when they see their food is wet

Recommendations
> 1. Provide rainy gears to raiders
> 2. Set up weather notification onward 2 hours which applied with the data given
> 3. Pay extra wage / any welfare as reward for riders who attend rainy period which can motivate them to work
> 4. Allocate resouces, for example, contact EV mini cars and EV bikes merchandise to deal partners and make contract to raiders who are willing to drive

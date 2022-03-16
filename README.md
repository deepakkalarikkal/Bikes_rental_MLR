# Bike Sharing System
### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.?
How well those variables describe the bike demands?




## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
- What is the background of your project?
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- What is the business probem that your project is trying to solve?
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- What is the dataset that is being used?
The 'day.csv' data set is being used

## Conclusions

Categorical variable analysis
1. Seasons, 2. Month, 3. Years, 4. Weekdays, 5, weather where analysed by plotting boxplot and bar plots

In seasons vs total number of users
In Fall we have the highest number of users
And spring we have the least

In Months vs total number of users
The Month of September showed the highest number of users 
The Month of Jan showed the least number

In Years vs total number of users
The year 2019 saw a rise in total number of users in comparison to 2018.

In Weekdays vs total number of users
Weekdays had more number of users as compared to weekends but weekdays we have 5 days in comparison to weekend of two days.

Weather vs Total number of users
The number of users where more on a clear weather day followed by mist and cloudy day

Multiple Linear Regression Analysis
How various independent variables effect the Target variable. 
Our equation of Multi-Linear regression line is:
### Y= -0.3753 +(0.2313* workingday) +(0.4227 *temp)-(0.6877* spring) -(0.3539*July)- (0.2747*Sat)-(1.2958 * Light Snow&Rain)-(0.3505*Mist&Cloudy)+(1.0415 * year2019)


- Workingday: Its coefficient is 0.2313
with p-value of 0 and VIF 2.24

- Temprature: Its coefficient is 0.5527 
with p-value of 0 and VIF 1.93. 

- Spring : Its coefficient is -0.6877
with p-value of 0 and VIF 2.02

- Month of July: Its coefficient -0.3539
with p-value of 0 and VIF 1.31

- Saturday : Its coefficient 0.2747
with p-value of 0 and VIF 1.31

- Weather Situation, Light Snow and Rain: Its coefficient -1.2958
with p-value of 0 and VIF 1.06

- Weather Situation, Misty and Cloudy : Its coefficient -0.3505
with p-value of 0 and VIF 1.50

- Year 2019, : Its coefficient 1.0430
with p-value of 0 and VIF 1.80




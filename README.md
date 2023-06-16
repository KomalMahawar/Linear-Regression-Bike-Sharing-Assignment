# Bike Sharing Assignment
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This repository contains the Linear Regression model for the Bike sharing service provider named BoomBikes.
- ### Background:
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- ### Business Problem:
- Which variables are significant in predicting the demand for shared bikes. How well these variables describe the bike demands basis on various meteorological surveys and people's styles.The service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

Dataset Provided: The dataset provided for this problem contains 730 records and 16 columns
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Train dataset R^2 : 0.836
- Test dataset R^2 : 0.805
- Train dataset Adjusted R^2 : 0.832
- Test dataset Adjusted R^2 : 0.795
From the above evaluation we can say that bikes demand depend on the following predictors for :
temp : denotes the temperature
year : denotes year for bike sharing
winter : denotes the season
sep : denotes September month
summer : denotes the season
sun : denotes Sunday
july : denotes July month
spring : denotes season
misty : denotes weather condition
windspeed : denotes weather condition
Light_Snowrain : denotes weather condition
Equation of Regression line; where Bi denotes the variables with i as the variable number in list of predictors mentioned above:
cnt = 0.203 + 0.491B1 + 0.233B2 + 0.081B3 + 0.072B4 + 0.047B5 - 0.044 B6 - 0.048B7 - 0.068B8 - 0.080B9 - 0.149B10 - 0.284*B11
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- IDE - Anaconda Jupyter Notebook and VS Code
- language - python v3.9
- library - pandas v1.4.4
- library - numpy v1.21.5
- library - matplotlib v3.5.2
- library - seaborn v0.11.2
- library - sklearn
- library - statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was a bussiness problem provided by UpGrad
- References:
- https://stackoverflow.com/
- https://www.kaggle.com/
- https://www.google.com/
- https://towardsdatascience.com/

## Contact
Created by [https://github.com/KomalMahawar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

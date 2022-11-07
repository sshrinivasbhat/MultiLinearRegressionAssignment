# Linear Regression Assignment
> 
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- Bikes are borrowed through computer-controlled docks and returned back to another dock.
- Revenue dips in US bike sharing provider due to Corona.
- Business plan is to accelerate the revenue as soon as ongoing lockdown come to an end.
- Understand the factors affecting the demand of the shard bikes in the American market
- Identify Variables significant in predicting the demand of shared bikes
- How well the variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	Linear regression assignment - MLR for a bike sharing system.
- Background
	- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
	- Bikes are borrowed through computer-controlled docks and returned back to another dock.
	- Revenue dips in US bike sharing provider due to Corona.
	- Business plan is to accelerate the revenue as soon as ongoing lockdown come to an end.
- Goal
	- Linear regression model  of Demand of Shared Bikes with the available Independent Variables.
	- Understand Demands variation with different featuires.
	- Manipulation of business strategy to meet the demand levels and expectations of the customer.
	- Understand Demand Dynamics of a new Market.
- What is the dataset that is being used?
	- day.csv (description in DataDictionary.txt)
	


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
	--------------------------------------------------------
	FIT IS WITH MIN-MAX SCALING ON DATA-SET
	Initial RFE Features Considered =  14
	-------------------------------------------------------
	Final Features and Coefficients
	------------------------------
	temp                  0.447379
	weatsit_3lightrain   -0.287028
	yr_2019               0.234598
	const                 0.214403
	windspeed            -0.151694
	m9                    0.091051
	holiday              -0.090982
	winter                0.086565
	spring               -0.082791
	weatsit_2cloudy      -0.079341
	m5                    0.064284
	m3                    0.054170
	m4                    0.053375
	m6                    0.036216
	dtype: float64
	-------------------------------------------------------
	Best Fitted Line 
	---------------- 
	cnt =  (0.2144)*const+(-0.091)*holiday+(0.4474)*temp+(-0.1517)*windspeed+(-0.0793)*weatsit_2cloudy+(-0.287)*weatsit_3lightrain+(-0.0828)*spring+(0.0866)*winter+(0.0542)*m3+(0.0534)*m4+(0.0643)*m5+(0.0362)*m6+(0.0911)*m9+(0.2346)*yr_2019
	-----------------SCORE ON TEST DATA--------------------
	Root Means Square Error =  0.09486832980505137
	MSE                     =  0.009
	R2 Score                =  0.811
	------------------SCORE ON TRAINING DATA---------------
	Root Means Square Error =  0.09110433579144299
	MSE                     =  0.0083
	R2 Score                =  0.835

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.9.x
- numpy - version  1.21.5
- pandas - version 1.4.2
- seaborn - version 0.11.2
- sklearn - version 1.0.2
- statsmodels - version 0.13.2
- scipy- version 1.7.3
- matplotlib- version 3.5.1


import warnings
warnings.filterwarnings('ignore')

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project executed is an graded assignment from upgrad
- References - upgrad-course material , upgrad documents.



## Contact
Created by Shrinivas Bhat [@sshrinivasbhat] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
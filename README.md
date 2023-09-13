# Bike Sharing System Case Study
> Boom Bikes a bike sharing system need to identify significant factors contributing to demand of shared bikes. The organisation wants this information to have a mindful business plan to accelerate its revenue.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes has a bike-sharing system for use by individuals on short term basis for a price or free.
- Coming out of corona lockdowns, BoomBikes need mindful business plan to be able to accelerate its revenue.
- BoomBikes wants to understand:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- EDA on categorical variables
	- Clear Weather shows more demand for bikes, which decreases with increasing clouds and further dips with rain and snow.
	- Summer and fall show more demand for bikes compared to spring and winter season.

- EDA on numerical variables
	- Temperature and Absolute temperature show linear relationship with bike demand.

- Feature Selection
	- Following Manual and RFE base feature selection, the following features were most significant in predicting the demand for shared bikes.
		- Temperature, Windspeed, Season and Weather.

- Linear Regression model with the above selected features results in a r_square score of 0.76 on the test data 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.10
- pandas
- seaborn 
- statsmodels
- skelarn
- scipy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was in contribution to Linear Refression Assignment on Bike Sharing system by Upgrad.



## Contact
Created by [@RavMan1991] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

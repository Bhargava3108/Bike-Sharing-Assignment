# Bike Sharing system and Factors to enhance demand
> This assignment is a bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.The Business strategic to meet the demand level and meet the customer expetation.they want to understand the factors affecting the demand for these shared bikes in the American market. 


## Table of Contents
* [General Info]We have analyzed the bike sharing data provided between the years 2018 to 2019 and then we apply different methods to clean the data and to build a model on multiple linear regression
* [Technologies Used] Python,GIT,GITHUB
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
- What is the background of your project?
The Back ground of the project is to analyze bike sharing data collected across the time period 2018 -2019. The data contain 730 records along with 16 columns. The multiple linear regression model is being used as the methodology to analyze the data.

- What is the business probem that your project is trying to solve?
The Business Goal is to increase the demand and analysis various fators which are dependant to meet the demand levels and meet the customer's expectations.the model will be a good way for management to understand the demand dynamics of a new market. 

- What is the dataset that is being used?
The Bike sharing data is the master details dataset and Data dictionary is to understand the column meaning.


## Conclusions
- Conclusion :

-
cnt = 0.3661 + (0.2338 x yr) +(0.4577 x atemp) - (0.1640 x hum) - (0.1676 x windspeed) - (0.1040 x spring) +(0.0316 x winter) -(0.2462 x Light rain) -(0.0569 x Mist) -(0.0438 x Sunday) - (0.0429 x jan)- (0.0570 x jul) + (0.0721 x sep) + (0.0371 x may) +(0.0481 x oct)


 The Result shows that the data model demands for the bikes are depend on the Variables such us Year,atemp,Hmidity,windspeed,seasons,weather and Months

 Demand increases when the temperature is fine and winter with various months like sep,may,oct.

 Demand decreases when the Humidity increases, if there is light rain and mist and in spring seasons, holidays in the month of Jan and Jul.

  The Demand for the next year is dependant on the demand of this year.




## Technologies Used
python - version 3.6.9
pandas - version 1.0.3
matplotlib - version 3.2.1
seaborn - version 0.11.1



## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@@Bhargava3108] - feel free to contact me!



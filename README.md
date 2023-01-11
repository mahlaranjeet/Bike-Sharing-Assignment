# BikeRental-Regression-Assignment![image](https://user-images.githubusercontent.com/6258852/211809625-a9620c78-e86f-47ed-aacc-f76fa933b9ed.png)


##SUBMITTED BY DR RANJEET SINGH MAHLA

##DATE JANUARY 11, 2023

##MSC MACHINE LEARNING AND ARTIFICIAL INTELLIGENCE 


### KEY FILES
###jupyter notbook containing model building code
### data (.csv file) boom bile rental data
### subjective questions on linear models and related topic

> PROBLEM STATEMENT
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    1) Which variables are significant in predicting the demand for shared bikes
    2) How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Information](#general-information)
* [Steps](#steps)
* [Essential Code](#essentai-code)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknoledgemenets](#acknoledgements)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- MULTIPLE LINEAR REGRESSION IS PERFORMED ON BIKE RENTAL DATA
- THIS PROJECT IS DONE TOWARDS AN ASSIGNMENT FOR MSC IN MACHINE LEARNING AND ARTIFICIAL INTELLIGENCE. 
- THIS PROJECT ESTIMATE THE KEY VARIABLES WHICH RELATE WITH BOOM BIKE RENTAL (some of the varaible represents to temperature, humidity, weather, holiday)
- IN THIS MODEL BOOM BIKE RENTAL DATA IS USED FOR BUILDING THE MODEL FOR BUSINESS RECOMMENDATIONS

### Steps 

1) Reading, understanding and visualizing the data

2) Preparing the data for model training (train-test split, rescaling)

3) Training the model

4) Residual analysis

5) Prediction and evaluation of the test set

### ESSENTIAL CODE 
from sklearn.metrics import r2_score
r2_score(y_test, y_pred)


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
BOTH TEST AND TRAIN DATASET MEAN SQUARED ERROR IS NEAR TO 0 SUGGEST THE ACCURACY OF MODEL
SIGNIFICANT VARIABLES ARE PRIDICTED BASED ON p-value and VIF
AUTOMATED SELECTION OF VARIABLES WAS DONE BY RFE


BIKE DEMAND IS LARGELY DEPENDS ON WEATHER AND TEMPERATURE
MORE BIKE RENTAL IN WINTER COMPARED WITH SUMMAR AND SPRING
HIGH RENTAL IN SEPTERMBER AND OCTOBER
MORE RENTAL ON WEDNESDAY, THRUSDAY AND SATURDAY 
MORE RENTAL ON HOLIDAYS


BUSINESS RECOMMENDATION

COMPANY SHOULD FOCUS ON MARKETING IN SUMMAR AND SPRING
INTRODUCE MORE USERS OR DECREASE RENTAL PRICE IN SUMMAR AND SPRING
MORE RENTAL OCCURED IN 2019, SO PEOPLE ARE TAKING IDEA AHEAD AND THESE CUSTOMERS SHOULD BE RETAINED 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- matplotlib
- statsmodels
- sci-kit learn
- numpy
- pandas
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## ACKNOLEDGEMENTS
-This project was inspired by upGrad case study for AI and ML (BOOM BIKE RENTALS)
-This project is submitted towards frist case study of MSC in AI and ML 

## Contact
@mahlaranjeet
mahlaranjeet@gmail.com

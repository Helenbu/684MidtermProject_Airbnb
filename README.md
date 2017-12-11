## Midterm Project_Airbnb

# Introduction

This project is designed to display data analysis based on Inside Airbnb data set from http://insideairbnb.com/get-the-data.html. Datas contain two cities: Boston and New York City. For each city, I used property listing data. 

The project is focused on the difference of properties between two cities. Taking from there, we can see some potential market strategies to promote offers from each city, from company's perspective; or we can see the bargain strategies when we as guests to choose stayover places when we visit the cities.

The major procedure can be summarized as below: 
1. Explorary Data Analysis and Visualization
2. Multi-level linear model on price prediction
3. Model Checking
4. Reference and appendix 

Due to time limit, the project is only able to explore some aspects. The analysis has limitations on such as safety control, walk score and social interaction between landlords and guests. Feel free to contact me if you have any suggestions! 

## Data Overview

After data cleaning, Boston has 3925 properties on the list and New York City has 33938 properties on the list. The total 36 variables contain property information, host information and hosting rules. 

For the outcome variable, I define the price by creating new variable, the price per person, which equals sum of price and cleaning fee divided by guests_included. $$Price\,per\,person = \dfrac{(Price + Cleaning\,fee) }{Guests\,included} $$ 

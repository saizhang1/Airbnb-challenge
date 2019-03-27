# Airbnb-challenge
Comparing the Boston and Seattle Airbnb accommodation information, find the most relevant features to predict the price.

# Table of Content
* Project Motivation

* File Description

* Business questions

* Result/Key Findings

* Acknowledgments

## Project Motivation

I am looking to really challenge myself, data from Seattle and Boston AirBNB homes can be used to understand how much AirBNB 
homes are earning in certain time frames and areas. I can compare rates between the two cities, or try to understand if there is 
anything about the properties that helps to predict price. This dataset requires a number of skills beyond those shown thus far in my 
data science course, this will certainly test my ability to work with messy, real world data.

## File Description

The following Airbnb activity is included in this Boston and Seattle dataset: * Listings, including full descriptions and average review score * Calendar, including listing id and the price and availability for that day.

## Business Questions

- How is the evolution of price along the years and month in Boston?
- How do we compare the evolution of price between Boston and Seattle?
- What are the features most influence on the price?
- Are the most predictive features of Seattle different from Boston?

## Results / Key Findings

### The relationship between the price and the number of houses.

> Boston
![boston](https://user-images.githubusercontent.com/36822899/54990956-33062f00-4fbc-11e9-9ee2-6518783587aa.PNG)

> Seattle
![seattle](https://user-images.githubusercontent.com/36822899/54990976-3bf70080-4fbc-11e9-9412-1b030f4fba22.PNG)

#### Seattle VS Boston
As we can see from these 2 graphs of the evolution of the house price and number in Seattle and Boston. The trend of the numbers of house are the same. But you can see that the price has less impact on the number of the house in Seattle than Boston. The price of the house in Seattle has the peak at August 2019 because of the summer season, later it decreases. But the price in Boston keeps high from May to October.

### Most predictive features for the price.

> Boston
![boston 1](https://user-images.githubusercontent.com/36822899/54991081-782a6100-4fbc-11e9-956e-307166bd6301.PNG)

> Seattle
![seattle 2](https://user-images.githubusercontent.com/36822899/54991064-6e086280-4fbc-11e9-9eea-9f04e214ccc9.PNG)

#### Seattle VS Boston

As you can see in Seattle, for the price trend, the most predictive features, lets say the features which influence most on the price change are:

-Number of bedrooms

-number of bathrooms

-number of beds

-number of reviews

-Neighbourhoods

In Boston, the most predictive Features are:

-Number of beds

-Self check in system

-Private room type

-Number of bathrooms

-City center of Boston

## Acknowledgement

This dataset is part of Airbnb Inside, and the original source can be found [here](http://insideairbnb.com/get-the-data.html)

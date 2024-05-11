# AirBnB-prelim-analysis

## Introduction
The goal of this project is to understand the AirBnB business via its dataset, which relates to the 2016 data for the city of Seattle.
The dataset consists of three separate tables :
> * calendar.csv : This holds data of the various times a rental unit was used and its related data
> * listings.csv : This holds data of each rental unit as well as inforation on the host
> * reviews.csv : This holds data of reviews give each time a unit was rented. This dataset is not used in the analysis.

In our analysis we will try to answer these questions:
> * Which house is the most popular type in each area?
> * When does each house have the highest price?
> * What features help determine the house price, i.e. can we suggest an optimal price point for a give rental unit?

The information of most important columns used in each dataset is given below:
> *calendar.csv*
> * **listing_id** : Unique identifer for rental unit
> * **date** : When the unit was rented (datetime)
> * **available** : whether unit was rented on that date ( boolean)
> * **price** : Price per day for rental (float)

> *listings.csv*
> * **id** : Unique identifer for rental unit
> * **host_response_time** : response time for host ( categorical data)
> * **host_response_rate** : response rate of host ( percentage)
> * **host_is_superhost** : Whether host is a superhost or not (boolean)
> * **neighbourhood_cleansed** : neighborhood of the unit. Some preliminary processing has been applied to it
> * **zipcode** : Zip code of the unit
> * **property_type** : type of unit, e.g. apartment, house, tent, etc.
> * **acomodates** : number of people for default charges
> * **bathrooms** : number of bathrooms available
> * **bedroons** : number of bedrooms
> * **amenities** : list of amenities available in the unit
> * **price** : cost (USD) per night
> * **review_scores_rating** : unit review out of 5

The project dealt with the follwing steps:
#### Business and Data Understanding
> We parsed the dataset to understand what metrics were of most importance in Seattle for AirBnB
> We also looked at what features in each dataset were of highest importance for us to furhter explore

#### Data Preparation
> Having shortlisted the data we want to focus on, we have performed data wrangling to:
> * Filter out columns we dont want to process further
> * Deal with NaNs in our Dataset
> * Deal with categorical columns and encode as one-hot for our Linear Regression model

#### Data modelling and Result Evaluation
> In this step, we built charts and ML models to help understand the relation of verious metrics with respect to each other or wrt time.
> We have gleamed questions of interest from the data and have answered these with charts and models.


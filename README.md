# Linear Regression Project
## Predicting Home Sales Price using common home features

![alttext](https://i.ibb.co/s9r59x2/Seattle-Rainier-photo.jpg)

## Overview

Regression models are the foundation of machine learning. Any competent machine learning engineer and data scientist must be comfortable with many kinds of models, but none is more foundational than a linear regression model. In  this project we (a team of two) aimed to train, test, and deploy a linear regression model to predict the sales price of homes in King County, Washington. Our aim for this project was to create a model that could not only predicted the price of a home, but do so with a reasonable degree of certainty. We were able to achieve an R-Squared score of 0.85 on our testing score, while also limiting our features to the 13 most essential attributes of a home in Washington. A conscious effort was made to limit our features in order to prevent over-fitting and for the sake of scalability. 

## Business Understanding

Thinking about breaking into the Airbnb rental market in King County, Washington?  Situated around Seattle, King County is a great market for vacation and business trip rentals due to its nearby National Parks, vibrant culture, and prominent business headquarters such as Amazon, Microsoft, and Starbucks.

Which features contribute the most to an Airbnb’s profit? You would want to know if a house is a good investment, and to do that you would need to know an estimate on the potential revenue of a property and its cost. Our regression model predicts the sales price of a house, which we then compare to an estimate of revenue generated by similar homes in that zipcode to decide if that property is likely to be profitable.

## Data Understanding and Analysis

There were three main data sources used for this project. The first was a CSV files with 25,000 rows. This csv file contained basic information on homes sold in King County between 2014 and 2015. Some of the example features were the square footage of the living room, lot, and neighboring houses as well as the number of bedrooms, bathrooms, and the presence of a basement. There were a total of 15 different features for each home, and more information is provided in our data folder in the columns.rm. In addition to the King county dataset we were able to scrape data from the entire state of Washington. This data was pulled from this website.   This data was used to determine the average household income per zipcode and was used as a feature of our model. Lastly, the third dataset was a csv with airbnb listings in the Seattle area with a few descriptors of each listing as well as their location based on latitude and longitude. The airbnb data for Seattle , listed as listings.csv.gz, can be downloaded from this website. These three datasets alongside some national statistics of airbnb rentals was used to train our model and answer our business question. 
 
## Description of data

Our baseline model: 
![alttext](https://i.ibb.co/2gPCLmk/sales-price-sqft-living-model.png)

A sample distribution of some of our features with sales price: 
![alttext](https://i.ibb.co/2vj881n/top-3-features.png)

Our most correlated features used to train the model: 
![alttext](https://ibb.co/FDQKXYT)

Our final model visualized here: 
![alttext](https://i.ibb.co/SxqX2hV/model-final.png)



## Conclusion


(profit conclusion)
Smaller houses (between 1000-2000 square feet) yielded the highest profit margin. Effectively, as house prices increased, rental profit decreased. We recommend choosing a smaller to mid sized home, a little bit outside of Seattle. Housing prices are cheaper a little outside of the city, but the location is still easily commutable into downtown. Go with a smaller to mid sized home between $250,000 and $500,000, as these proved to be the most profitable. We specifically recommended the 98028 zip code, the town of Kenmore Washington, as it had the highest average  Airbnb nightly rates and revenue. 

# BlogPost
for udacity project
# Motivation

The purpose of the project is to create a model for forecasting the the price of Airbnbs in Seattle for 2016-2017 data.

Main questions to be answered within the project:

- How accurate price prediction model can be in this case?
- What are the top 10 features impacting AirBnB price?
- What owners should play with to get higher rating score?

# Dataset:
Only listing.csv file was used from the dataset
https://www.kaggle.com/airbnb/seattle

- Listings data with information on hosts, prices, ratings, etc.

# Libraries

 - pandas == '1.0.1'
 - numpy == '1.18.1'
 - seaborn == '0.10.0'
 - matplotlib == 3.1.3
 - scikit-learn ==  0.23.0.
 
 - conda v == 4.8.2
 - python v == 3.7.6



# Files

project2.ipnb

# Conclusion
- Neighbourhoods with the most listing counts are located mostly in the city centre.
- In this article, we reached 60% of accuracy and MSE=14.
- We found out that that property and room type, location, extra guests, bedroom and bathroom counts are mostly affecting the price.
- After looking at the data we figured out that price doesn`t have much impact on price, What has is amenities. So hosts may enrich and focus on their service provided in order to get a higher score.



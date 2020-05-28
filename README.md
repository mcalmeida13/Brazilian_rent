# Brazilian rent price: Data analysis

## Motivation
This notebook is going to be focused on predicting house rent in five cities of Brazil.

A house value is simply more than location and square footage. We are going to take advantage of all of the feature variables available to use and use it to analyze and predict house rent prices.

We are going to break everything into logical steps that allow us to ensure the cleanest, most realistic data for our model to make accurate predictions from.

## Understanding the Client and their Problem

A benefit to this study is that we can have two clients at the same time! (Think of being a divorce lawyer for both interested parties) However, in this case, we can have both clients with no conflict of interest!

Client Housebuyer: This client wants to find their next dream home with a reasonable price tag. They have their locations of interest ready. Now, they want to know if the house price matches the house value. With this study, they can understand which features (ex. Number of bathrooms, location, etc.) influence the final price of the house. If all matches, they can ensure that they are getting a fair price.

Client Houseseller: Think of the average house-flipper. This client wants to take advantage of the features that influence a house price the most. They typically want to buy a house at a low price and invest on the features that will give the highest return. For example, buying a house at a good location but small square footage. The client will invest on making rooms at a small cost to get a large return. 

Our data comes from a Kaggle competition named “brazilian_houses_to_rent” (<url>https://www.kaggle.com/rubenssjr/brasilian-houses-to-rent</url>), which is a dataset houses to rent in diferents cities in Brazil. It contains 10962 training data points and 13 features that might help us predict the selling price of a house.

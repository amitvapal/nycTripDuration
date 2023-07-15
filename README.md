# nycTripDuration

This project builds a model to predict the trip duration for NYC taxi rides based on pickup time, pickup location, and other features.

Data

The data comes from the NYC Taxi Trip Duration Kaggle dataset. It contains the following features:

pickup_datetime - timestamp when the taxi ride started

pickup_longitude - longitude coordinate of where the taxi ride started

pickup_latitude - latitude coordinate of where the taxi ride started

dropoff_longitude - longitude coordinate of where the taxi ride ended

dropoff_latitude - latitude coordinate of where the taxi ride ended

passenger_count - number of passengers in the taxi ride

The target variable is trip_duration - the length of the taxi ride in seconds.

Approach

The steps for this project were:

1. Loading and exploring the data
2. Feature engineering from datetime data
3. Training a linear regression model to predict trip duration
4. Evaluating the model on test data
5. Plotting coefficents to see which features have high variance

The model performance is evaluated using RMSE.

## Restaurant Turnover Prediction

![restaurant](https://github.com/user-attachments/assets/1e80c4ae-101b-48ea-8c07-63058de6252f)

## Objective

The first thing any visitor to India will take in — probably while staring out the window in awe as their aeroplane descends is the sheer size of this country. It is densely populated and patchworked with distinct neighbourhoods, each with its own culinary identity. It would take several lifetimes to get to know all of the street stands, holes in the wall, neighbourhood favourites, and high-end destinations in this city. And for Indians dining out is and always will be a joyous occasion. Everyone has their own favourite restaurants in the city starting from the street food stall across the street to the 5-star restaurants in the heart of the city. Some are favourites because of the memory attached to it and some are favourites because of the fact that the place has a fantastic ambience. There are a lot of other factors as well which contribute to the likeness of the restaurants which in turn determines their popularity among masses. 

If you look at this from the business perspective for a restaurant, more popularity may mean more visits to the joint increasing the annual turnover of the restaurants. For any restaurant to survive and do well, the annual turnover of the restaurants has to be substantial. 

This problem takes a shot at predicting the annual turnover of a set of restaurants across India based on a set of variables given in the data set. This includes the data related to the restaurant such as location, opening date, cuisine type, themes etc. This also includes data pooled from different sources such as social media popularity index, Zomato ratings, etc. Lastly, it also adds a different flavour to the problem by looking at the Customer survey data as well as ratings provided by a mystery visitor data (audit done by a third party).

## Hackathon

The Hackathon was conducted by Great Learning on Sep-2024 and the provided data had 3993 records of restaurant's turnover.

## Data Preprocessing

- Dropped redundant variable.
- Encoded categorical variables.
- Bucketed numerical variable whichever has missing values.
- Transformed variable according to Machine language.
- Standardized the data to ensure each feature contributes equally by scaling all features to a common scale

## Winning Model

- Did Hyperparameter tuning and got the best least RMSE by SGD Regressor.

![DSE+Hackathon+Winner-Sep24+%281%29](https://github.com/user-attachments/assets/f16624fb-6cd6-447f-92a8-876c9f812f6f)

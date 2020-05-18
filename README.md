# Machine Learning Project - Exoplanet Exploration

## Note

Understanding of testing and tuning different Classification models in Machine Learining.

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, this creates a machine learning model capable of classifying candidate exoplanets from the raw dataset.


### Preprocessing Data

* Processed the data prior to fitting the model.
* Used `MinMaxScaler` to scale the numerical data.
* Separated the data into training and testing data.

### Tune Model Parameters

* Used `GridSearch` to tune model parameters.
* Tuned and compared two different classifiers. I used models Logistical Regression and Single Vector Classification.

### Reporting

The logistical regression model with GridSearchCV tunning is the best model to predic new exoplanets. During the intitial run of fitting and training the model, it resulted in just a 28% effectiveness in predicting new exoplanets but after applying GridSearchCV to it improved to 88% of predictive possitlitites. 



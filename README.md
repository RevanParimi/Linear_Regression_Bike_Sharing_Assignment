# Linear_Regression_Bike_Sharing_Assignment


## Technologies Used
1. Numpy
2. Pandas
3. Seaborn
4. Matplotlib.plt
5. Sklearn
6. Statsmodels

## Data Visualization

1. Data Handling and Cleaning
2. Missing Value Treatment
3. Identifying and Removing Outliers
4. Divide into categorical variables and numeric variables

Insights described in the readme file
weathersit :
     1: Clear, Few clouds, Partly cloudy, Partly cloudy
     2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
     3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
     4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
Season :
    1: spring 
    2: summer 
    3: fall
    4: winter
Year (yr)
    0: 2018
    1: 2019       
Month (mnth)
mnth : 1 to 12

5. Map the columns to their respective descriptions
6. Unilateral and Bilateral Plotting

## Data Preparation

1. Adding Dummy variables
2. Split train test dataset
3. Data Scalling
4. Split data into X and y (train and test dataset)

## Data Modelling and Evaluation

1. RFE - Recursive Feature Elimination
2. Drop variable and update model
3. Prediction on test set
4. Evaluate the model on test set

## Conclusions

The equation of fitted line is:

cnt=0.077+(0.235×yr)-(0.082×holiday)+(0.570×temp)−(0.090×windspeed)+(0.073×season_summer)+(0.127×season_winter)+(0.090×mnth_sp)−(0.232×weathersit_Light Snow & Rain)

From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 73% of bike demand.
Coeffiencients of the variables explains the factors effecting the bike demand
Based on final model top three features contributing significantly towards explaining the demand are:

temp (0.570)
weathersit_Light Snow & Rain (-0.232)
yr (0.235)
We can conclude that the above variables gives utmost importance for planning maximum demand.


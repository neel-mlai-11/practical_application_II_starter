OVERVIEW:

In this application, you will explore a dataset from kaggle. The original dataset contained information on 3 million used cars.
The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. 
As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car

Business Understanding:

The primary objective of the analysis is to understand the factors that influence the pricing of used cars. By analyzing the dataset, the goal is to identify key features or characteristics of used cars 
that contribute to higher or lower prices.The analysis will focus on a dataset containing information on 426,000 used cars. The dataset includes various attributes such as the car's year of manufacture, 
make and model, condition, odometer reading, fuel type, transmission type, and more. Data preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical 
features will be necessary to prepare the data for modeling.

Data Analysis:

Looking at the above charts We can infer that
Most Cars are manufactured in year 2000 and afterwords
Most cars are with clean title
Most cars in good or excellent condition
Most cars have less than or equal to 8 cyllinders
Most cars are SUV, Sedan or Pickup/Truck
Most cars have odomter in 20000-30000
Most cars have fuel type as gas
Most cars have automatic transmission

Modeling:

Simple Linear regression and Lasso regression models are implemnted
Also implemented ridge model

Evaluation:

Errors are Calculated and plotted for simple regression and lasso models

Findings:

For both linear regression and lasso regression , Year and Cyllinder contributes to the price of the car.

Next steps:

column model has lots of data which could be filtered properly so number of uniq values could be reducded.

I tried to run with more filter with preserved data but ended up getting memory errors.


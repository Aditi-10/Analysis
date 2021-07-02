

# Goal: Zomato Bengaluru Restaurant Descriptive Analysis and Predicting Rating for each restaurant on the basis of its facilities and features.
## Data Acquire:
https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants
## Objectives
From all the Data available, we can bring out some neat insights or conclusions such as
Which franchise has the highest number of Restaurants?
How many Restaurants are accepting online orders?
How many have a book table facility?
Which location has the highest number of Restaurants?
How many types of Restaurant types are there?
What is the most liked Restaurant type?
What is the Average cost for 2 persons?
What is the most liked Dish type? and so on...
## Data Understanding
we have 51717 entries/records of Data with 17 columns.The columns are as follows, 
![Column Description](https://user-images.githubusercontent.com/82563399/124279767-7e2d2600-db65-11eb-8c38-7ae79578b2a3.jpeg)


After preprocessing the data, using data visualization each column and feature is explored and compared.
# Model building
we have columns/Feature called Online order and Book table which are Categorical variables and for machine learning to model work we should input numerical values to perform. hence used Label Encoding on these 2 Features that encode Yes/No as 0/1.Similarly on Features like “Location”, “Restaurant type”, and “Cuisines”.
## Different Models 
After training and testing , applied *Linear Regression, Random Forest, Decision Tree, Naive Bayes, KNN models* for prediction and its accuracy.

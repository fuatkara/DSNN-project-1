# DSNN-project-1

Discovery of Boston Airbnb Dataset

Business Understanding
   “Airbnb started in 2008 when two designers who had space to share hosted three travelers looking for a place to stay. Now, millions of hosts and travelers choose to create a free Airbnb account so they can list their space and book unique accommodations anywhere in the world.” says in their page. For hosts, It’s a way of having income. Another view is that users who are traveling and looking for stays research rooms by neighborhood or location. Airbnb recommends the best price in the neighborhood so that users can book the best deal in overall.

   In this project, Boston city airbnb will be analysed. Boston Airbnb listings dataset has various columns and features such as accomodates, bed, bedrooms, bathrooms, neighborhood, property type, price, reviews, ratings, etc. Thinking about what features are affecting the price in Boston city having some statistics about availability in Boston city would make us curious and excited. The following questions will be answered throughout this project.

1. What are the most efficient columns/features on the price in Boston City?
2. Trying to predict the price of Airbnb’s in Boston City ?
3. What is the availability by daily, weekly, monthly in Boston City ?

Data Understanding
Throughout data science studies, there are a few python libraries which help us to perform our data and understand better. In this study, Pandas, NumPy, Matplot, Seaborn, and Sklearn aka scikit learn are used to analyse, draw and build our model to understand data better. The below steps are followed;

* Import packages and read Boston Airbnb datasets
* Copying first dataset(listings) to work on it (for question 1),
* Converting to float the price column,
* Coralating the other columns with price column to see effeciency,
* Ensuring efficient column in price.
* Making some data cleaning and transformation (for question 2),
* Comparing ‘mean’ and ‘medium’ scores for the price column,
* Building a RandomForest model to predict r2_score,
* Evaluating the model,
* Using plt to show results.
* Reading the ‘calendar.csv’ dataset,
* Analysing the dataset (for question 3)
* Focusing on ‘Availability’ column
* Having some statistic study by day,week,month on Availability column in Calendar dataset.

Question 1 :
we have picked some features that might be useful for the predicting the price (as a recent data scientist eye :) ). We have checked features corelation with price. As we can see down blow, accommodates, square feet, beds, bedrooms are the most efficient features on the price.

![image](https://user-images.githubusercontent.com/95101910/145694577-c98d04eb-9e03-4b5d-a650-8649ec1bd6fe.png)


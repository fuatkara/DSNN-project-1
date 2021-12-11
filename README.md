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

Preparing the data 

In this section, we list the dataset and apply some steps such as converting the type and prepating it for modelling.

![Ekran Resmi 2021-12-12 02 43 26](https://user-images.githubusercontent.com/95101910/145695087-28ed9902-1760-4a0f-ac24-91864205e858.png)

![Ekran Resmi 2021-12-12 02 50 11](https://user-images.githubusercontent.com/95101910/145695221-6c92e28f-8871-4c60-b6cf-03640d7a6d99.png)


Question 1 :
we have picked some features that might be useful for the predicting the price (as a recent data scientist eye :) ). We have checked features corelation with price. As we can see down blow, accommodates, square feet, beds, bedrooms are the most efficient features on the price.

![image](https://user-images.githubusercontent.com/95101910/145694577-c98d04eb-9e03-4b5d-a650-8649ec1bd6fe.png)

Ensuring the corelation rates with price column;

![image](https://user-images.githubusercontent.com/95101910/145694741-77912b27-718f-43ec-ab76-f4e261cd1145.png)

Question 2 : 
First, we check about numeric statistic for the price. Compared ‘mean’ and ‘median’ metrics and applied some data cleaning steps such as dropping and choosing important features to predict the price.

![image](https://user-images.githubusercontent.com/95101910/145694755-276869c4-823d-46ef-984a-d7e770202e7b.png)

![image](https://user-images.githubusercontent.com/95101910/145694758-db4868a4-3e27-4057-b73a-e40a42cdd2a2.png)

The r-squared score for your model was 0.3351947946823851 on 12 values. That shows us that we need to focus on the parameters more.

Question 3: 
We’re focusing on the calendar.csv file to predict availability level. We’ve seen that availability features includes ‘t’ as true and ‘f’ as false. After converting to 1 to ‘t’ and 0 to ‘f’, we get ready to make some statistics about the data.

![image](https://user-images.githubusercontent.com/95101910/145694781-91483b5c-b690-4da3-b9f2-003d74fbe22b.png)

and here is some plots for the analysis;

![image](https://user-images.githubusercontent.com/95101910/145694790-061a2928-a690-4686-bc26-ad72db2675b8.png)

![image](https://user-images.githubusercontent.com/95101910/145694834-65361a70-e76a-4a30-ba6e-5feb6661daa1.png)

![image](https://user-images.githubusercontent.com/95101910/145694838-0e89da02-2a3d-4b1b-ae2e-4f225dc5dc57.png)

Evaluation 

Data science is leading the platforms to gain more customer and increase income. Analysing the data and taking some steps carefully what data tells us will make us lead the sectors.

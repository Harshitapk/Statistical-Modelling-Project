# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
This project aims to find meaningful information from different API's for a particular city using bike rentals data. It was achieved by collecting data about various venues around different bike stations and observe trends. I chose restaturants category to find out what are the options tourists have if they want to explore the city on a bike and what are crowded places on the basis of Reviews,ratings,price and payment facilities.

## Process
### 1.Data Collection 
- Collect data from multiple API's to have a comprehansive dataset to observe a trend. In this case, citybikes, foursquare and yelp were used to fetch the data using python.

### 2.Data Cleaning
- Identify and handle missing values in columns. You can fill missing values using the mean, median, or mode of the column or drop rows/columns with missing values based on the context.
- Check for and remove duplicate rows from the dataset. Duplicates can skew analysis results.
- Ensure that columns have the correct data types.
- Convert categorical variables into numerical values using techniques like one-hot encoding or label encoding.
- Store relevant information in Dataframes and convert into csv's for further analysis.

### 3.Joining Data
- Combine data from datasets created previously and observe trends.

### 4.Data visualization for EDA
- Create plots to understand the data, discovering patterns and spotting anomalies.
- I used Seaborn Python data visualization library based on Matplotlib as it provides a high-level interface for creating attractive and informative statistical graphics.

### 5. Data Model
- Build Multiple Linear Regression Model to understand the relationship between a dependent variable (or target) and one or more independent variables (or predictors).
- I used it predict/find empty slots based on features ['Bikes Available', 'Slots','Ebikes'] 

## Results
- It could be observed that bike stations where credit card is accepted are more occupied than where only cash is accepted. As a tourist one does not need to worry as mostly bike stations accept credit card.
- The diversity of restaurants is amazing, one can get food from almost all nationalities.
- Below Categories where bike slots are most occupied:
Categories                            Percentage
French, Lounges                       95.348837
Breakfast & Brunch                    95.348837
Bars, Modern European                 95.348837
Chimney Cakes, Cafes, Coffee & Tea    95.348837
Tex-Mex                               95.348837
- Assuming occupancy of bike slots correspont to number of people in that area, a fact was observed that tourists prefer price and reviews over rating to have food.

## Challenges 
I am completely new to this entire process of Data Analysis, first time working with python and API's I had a hard time collecting data and parsing data in dictionaries. It is difficult to conclude observations with limited data and time constraint.
Needed time to understand various aspects on building model and statistics involved in it.

## Future Goals
I want to explore other POI's as well so that I can create a reference model to develop a city as tourist destination. How to make a visit convenient for people coming from around the world and enjoy their time in a new city like create an app for tourists where they can find all local details (taxi, bikes, restaurants,hotels,currency exchange, netbanking,etc.)

The flow of the case study is as below:

Reading the data in python
Defining the problem statement
Identifying the Target variable
Looking at the distribution of Target variable
Basic Data exploration
Feature Engineering
Rejecting useless columns
Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
Feature Selection based on data distribution
Outlier treatment
Missing Values treatment
Visual correlation analysis
Statistical correlation analysis (Feature Selection)
Converting data to numeric for ML
Sampling and K-fold cross validation
Trying multiple Regression algorithms
Selecting the best Model
Deploying the best model in production
I know its a long list!! Take a deep breath... and let us get started!


Reading the data into python
This is one of the most important steps in machine learning! You must understand the data and the domain well before trying to apply any machine learning algorithm.

The data has one file "ZomatoData.csv". This file contains 9551 restaurants details.

Data description
The business meaning of each column in the data is as below

Restaurant ID: The id for each restaurant
Restaurant Name: The brand/restaurant name
Country Code: In which country the restaurant is operating
City: In which city the restaurant is operating
Address: What is the address of the restaurant
Locality: What is the locality of the restaurant
Locality Verbose: Detailed locality description
Longitude: GPS longitude location
Latitude: GPS latitude location
Cuisines: Various type of food offered
Currency: The business currency
Has Table booking: Is advance table booking facility available?
Has Online delivery: Does they take online food orders?
Is delivering now: Is is open now?
Switch to order menu: Whether switch to order menu is available?
Price range: The price range of the restaurant
Votes: The number of people who voted for the rating
Average Cost for two: The typical cost for two people
Rating: The final rating of the restaurant

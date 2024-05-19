Performance Analysis of Players and Fantasy 11

Group Members
- Adarsh Rao Akula
- Hyma Roshini Gompa
- Sai Varun Kotha
- Shri Aiswarya Gorle
- Sujeeth Reddy Sithagari

Introduction
This project involves analyzing cricketers' performance to gain insights into individual statistics, match results, and team dynamics. It aims to identify key players and assist in strategic planning.

Understanding the Dataset
Data source: Kaggle
Description: The dataset includes T20 stats of players worldwide since 2007.
Components: Three datasets for batting, bowling, and fielding, containing various statistics such as batting average, strike rate, wickets taken, team performance records, and match outcomes.

 EDA Analysis
- Replaced null values with column means.
- Renamed columns accordingly.
- Removed unwanted columns.

Proposed Algorithms
Supervised Learning
1. Decision Trees: Classifies players based on performance metrics into categories such as high, medium, or low scorers.
2. Logistic Regression: Predicts binary outcomes, such as whether a player will score a century in the next match.

Unsupervised Learning
1. K-Means Clustering: Groups players into clusters based on performance metrics to identify patterns and categories.

Feature Engineering Methods
Weighted Average Method: Calculates a weighted average of runs scored by each player, emphasizing the number of matches played to provide a comprehensive measure of batting performance.


Batting Analysis Using Linear Regression

 Data Preparation
- Removed unnecessary columns.
- Converted 'Runs', 'Balls Faced', and 'Strike Rate' to numeric values.
- Handled missing values by filling them with column means.

Feature Selection
- Chose 'Runs', 'Balls Faced', and 'Strike Rate' for predicting batting averages.

Model Training
- Split data into 80-20 ratio for training and testing.
- Trained a Linear Regression model on the training dataset.

Performance Prediction
- Predicted batting averages and ranked batsmen based on predictions and actual strike rates.

 Bowling Analysis Using Decision Tree Regression

 Data Preparation
- Removed unnecessary columns.
- Converted 'Wickets' and 'Average' to numeric values.
- Handled missing values by filling them with column means.

 Feature Selection
- Selected 'Wickets' for predicting average runs conceded per wicket.

Model Training
- Split data into 80-20 ratio for training and testing.
- Trained a Decision Tree Regression model on the training dataset.

Performance Prediction
- Predicted average runs conceded per wicket and ranked bowlers based on wickets taken and predicted averages.

Calculation of Weighted Average Runs in T20 Cricket
- Computes the weighted average of runs, emphasizing consistent performance over more games, and provides a deeper insight into scoring efficiency.

Calculation of Weighted Average Bowling in T20 Cricket
- Calculates the weighted average of bowling averages, emphasizing bowlers' performance over many games, and provides a nuanced view of bowling efficiency.

 Cricket Bowling Performance Clustering

 Data Preparation
- Converted bowling statistics to numeric values.
- Cleaned the dataset by removing rows with missing data.

 Feature Normalization
- Standardized the bowling statistics for equal importance in clustering analysis.

Model Training
- Implemented K-means clustering with four clusters to categorize bowlers.

Analysis and Visualization
- Visualized clusters using pair plots and analyzed centroids to understand the characteristics of each group.

Cricket Batting Performance Clustering

 Data Preparation
- Converted performance metrics to numeric values.
- Cleaned the dataset by removing rows with missing data.

Feature Normalization
- Standardized the performance metrics.

Model Training
- Implemented K-means clustering with four clusters to categorize players.

 Analysis and Visualization
- Visualized clusters and interpreted characteristics by analyzing centroids.

 Fantasy 11

Data Preparation
- Converted data for top T20 bowlers and batsmen into Pandas Data Frames.

 Data Shuffling
- Randomly shuffled data frames to eliminate ordering bias.

Selection and Display
- Selected top performers based on key metrics and displayed results.


![image](https://github.com/Adarshraoakula/PERFORMANCE-ANALYSIS-OF-PLAYERS-AND-FANSTASY-11-/assets/161667475/69c51e7a-abb9-4eef-95d7-6569eda01b25)

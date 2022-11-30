# NBA-Salary-Prediction
A multiple linear regression to predict an NBA player's salary based on various features.

## Step 1: Loading Datasets
Using Google Colab, I uploaded the NBA player datasets from Google Drive into the notebook.

## Step 2: Data Cleaning
I removed columns that did not have necessary information, removed rows with missing values, and generally formatted the dataframes for easier manipulation. After doing so, I merged datasets that were separated by year into larger tables for testing and training datasets. Finally, I manually one-hot-encoded the Position a Player played as well as the team(s) they were on.

## Step 3: Preliminary EDA
Before modeling, I checked the linear relationship between Salary (our y-variable) and a few features.

## Step 4: Modeling
I used three modeling methods to see results: Linear Regression, CART, and ADA boosting. Also plotted histograms of results and visualized a decision tree with CART. In the end, was able to come to conclusions about undervalued and overvalued players.

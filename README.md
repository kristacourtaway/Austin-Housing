# Austin Housing R Project

The provided R code is a comprehensive analysis script focused on housing data, performing various exploratory, statistical, and predictive tasks. It consists of the following key sections:

Libraries and Data Loading: Loads essential libraries such as tidyverse, caret, and ggplot2 and reads the "austinHousingData.csv" file.

Data Preparation Functions: Defines functions to handle missing values and split the dataset into training and testing parts.

Descriptive Analytics: Selects relevant features and computes summary statistics such as mean, median, and standard deviation. It also visualizes the distribution of selected features through histograms and assesses relationships between particular variables using correlations, box plots, and contingency tables.

School Analysis: Analyzes the impact of school-related features on housing prices through linear regression and visualizes relationships using pairwise plots.

Time Series Analysis: Conducts a time series analysis on the latest sale date and price, fitting an ARIMA model and forecasting future prices.

Geospatial Analysis: Visualizes property locations using spatial points data frames and ggplot.

Text Analysis: Preprocesses text data in the description field, extracts sentiment scores, and visualizes sentiment categories through density plots and bar plots.

Predictive Modeling: Performs predictive modeling using linear regression to predict housing prices and Random Forests for classification tasks. It includes preprocessing steps such as handling missing values and feature selection and evaluating the model's performance using metrics like Root Mean Squared Error (RMSE) and accuracy.

In summary, this code provides a multifaceted analysis. Encompassing descriptive statistics, visualizations, regression modeling, time series forecasting, geospatial mapping, text sentiment analysis, and predictive modeling. It illustrates a holistic approach to data analysis, covering various data dimensions.

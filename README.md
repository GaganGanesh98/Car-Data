# Car Data Analysis and Visualization
This project analyzes a dataset of car models to uncover insights about car prices, fuel efficiency, and other attributes. The analysis includes data cleaning, exploratory data analysis (EDA), and machine learning models to predict car prices and classify car types. Visualizations are created using ggplot2 and rpart.plot to make the findings more interpretable.

# Key Features
Data Cleaning: Missing values are handled, and categorical columns are converted to factors.

# Exploratory Data Analysis (EDA):
Average MSRP (Manufacturer's Suggested Retail Price) by car brand.
Relationship between horsepower and MSRP.
Fuel efficiency (MPG) analysis by car brand.
Relationship between car weight and city MPG

# Machine Learning:
K-Means Clustering: Groups similar car models based on attributes like price, horsepower, and fuel efficiency.
Decision Tree: Predicts car type (SUV, Sedan, Truck) based on horsepower, engine size, and weight.
Linear Regression: Predicts car prices (MSRP) based on horsepower, engine size, weight, and fuel efficiency

# Tools and Libraries Used
R Programming
Tidyverse (dplyr, ggplot2, readr)
Machine Learning Libraries (caret, rpart, rpart.plot, cluster)
Data Visualization (ggplot2, rpart.plot, viridis for colorblind-friendly palettes)

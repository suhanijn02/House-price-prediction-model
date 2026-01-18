# House-price-prediction-model
📌 Project Overview
This project aims to predict the median house value in California districts based on metrics from the 1990 census. This is a classic regression task where the goal is to build a model that can accurately estimate prices given features like location, income levels, and housing characteristics.
📊 Dataset Information
The dataset used is the California Housing Dataset, which contains 20,640 observations and 10 variables:Target: median_house_valueFeatures: Longitude, Latitude, Housing Median Age, Total Rooms, Total Bedrooms, Population, Households, Median Income, and Ocean Proximity.
🛠️ Key Technical Steps
Exploratory Data Analysis (EDA): Visualized geographical data to find correlations between location (coastal areas) and price.
Data Cleaning: Handled missing values in total_bedrooms using median imputation.
Feature Engineering: Created new meaningful attributes such as:rooms_per_householdbedrooms_per_roompopulation_per_household.
Data Preprocessing: Implemented a pipeline for Scikit-Learn using StandardScaler for numerical scaling and OneHotEncoder for categorical variables.
Model Selection: Evaluated multiple models including:Linear Regression , Decision Tree Regressor and Random Forest Regressor (Best Performer)
📈 ResultsThe Random Forest model achieved the following performance on the test set:Root Mean Squared Error (RMSE) and R-Squared 

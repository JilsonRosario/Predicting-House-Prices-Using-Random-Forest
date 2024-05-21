# Predicting-House-Prices-Using-Random-Forest

#Introduction
In the dynamic landscape of real estate, accurately predicting house prices holds immense importance for various stakeholders, including buyers, sellers, investors, and policymakers. Leveraging advanced machine learning techniques offers a promising approach to tackle this challenge effectively. This report details the process of constructing a predictive model using a Random Forest Regressor, a robust algorithm renowned for its versatility and predictive power. Our focus lies on utilizing a synthetic dataset encompassing key features such as square footage, number of bedrooms, number of bathrooms, and the age of the house to forecast the price.

#Aim of the Project
The aim of this project is to develop a robust and accurate machine learning model to predict house prices based on various features such as square footage, number of bedrooms, number of bathrooms, and the age of the house. By leveraging the Random Forest Regressor algorithm, the goal is to analyze and understand the key factors influencing house prices and to provide reliable price predictions that can assist buyers, sellers, investors, and policymakers in making informed decisions in the real estate market.

#Dataset Description
The dataset contains 100 observations with the following features:

SquareFeet: The total area of the house in square feet.
Bedrooms: The number of bedrooms.
Bathrooms: The number of bathrooms.
Age: The age of the house in years.
Price: The price of the house in dollars (target variable).

Methodology
Data Collection and Preparation
Initial Inspection
The dataset was first inspected to ensure there were no missing values and to understand its structure. The dataset was found to be complete, with no missing values.

Data Splitting
The data was split into training and testing sets to evaluate the model's performance. An 80-20 split was used, ensuring that the model could be evaluated on unseen data.

Model Training
We chose the Random Forest Regressor due to its ability to handle various data types and model complex relationships. The model was initialized with 100 trees and trained on the training data.

Model Evaluation
The model's performance was evaluated using Mean Squared Error (MSE) and the R^2 score. The MSE measures the average squared difference between actual and predicted values, while the R^2 score quantifies the proportion of variance in house prices that is predictable from the features.

Feature Importance
To understand which features contribute the most to the prediction, we examined the feature importances. This helps in understanding the key factors that influence house prices.

Visualization
Visualizations were created to provide insights into the model's performance and the data's structure. These included plots of feature importances, actual vs. predicted prices, and residuals.

Results
Model Performance
The model achieved a Mean Squared Error (MSE) of approximately 83.4 billion and an R^2 score of approximately -0.292. The high MSE indicates significant errors in predictions, while the negative R^2 score suggests that the model performs worse than a simple average of the target variable.

Feature Importances
The analysis revealed that square footage was the most important feature, followed by the age of the house, number of bathrooms, and number of bedrooms.

Actual vs. Predicted Prices
The scatter plot of actual vs. predicted prices showed significant deviations, indicating that the model's predictions were not closely aligned with the actual prices.

Residuals Analysis
The residuals analysis indicated that the model's errors were not randomly distributed, suggesting potential areas for model improvement.

Statistical Analysis
Descriptive Statistics
The dataset's descriptive statistics provided insights into the central tendency and dispersion of the features. The mean and standard deviation of each feature helped in understanding the typical values and variability within the dataset.

Correlation Matrix
The correlation matrix showed the relationships between features. For instance, features like square footage and number of bedrooms might have strong correlations with the house price, influencing the model's predictions.

Conclusion
The Random Forest Regressor model built for predicting house prices demonstrated limited accuracy, as evidenced by the high MSE and negative R^2 score. The feature importance analysis indicated that square footage is the most significant predictor of house prices. However, the model's overall performance suggests the need for further optimization and potentially exploring other algorithms.

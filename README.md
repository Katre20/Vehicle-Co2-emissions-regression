VEHICLE-CO2-EMISSIONS-REGRESSION

About the Project

In this project, I used the Canadian vehicle emissions dataset (7,385 records) to build a model that predicts exact CO2 emissions. By going beyond basic numerical features and incorporating categorical variables, I significantly improved the model's accuracy.

Steps & Pipeline

 -Exploratory Data Analysis (EDA): Cleaned and inspected the data, checking relationships between features through visualizations.

 -Feature Engineering: Used pd.get_dummies (One-Hot Encoding) to convert text-based columns like Transmission and Fuel Type into numerical format for the model.

 -Model Training: Built a Linear Regression model using scikit-learn and split the data into training and testing sets.

 -Evaluation: Measured model performance using the R2 Score and Root Mean Squared Error (RMSE).

Results

Before adding categorical features, my baseline R2 score was around ~0.87. After the encoding process, the performance jumped dramatically:

R2 Score: 0.989 

RMSE: 6.08 g/km

The actual vs. predicted values plot also clearly shows the points closely hugging the ideal prediction line.

# House price Prediction

## Overview

This project demonstrates a simple implementation of linear regression to predict real estate prices based on various features such as the number of bedrooms, bathrooms, square footage, and more. The project also includes a visualization of the best fit line for one feature (sqft_living) against the target variable (price).

# Dataset
The dataset used in this project contains real estate data with the following columns:

price: The price of the property (target variable).

bedrooms: Number of bedrooms.

bathrooms: Number of bathrooms.

sqft_living: Square footage of living space.

sqft_lot: Square footage of the lot.

floors: Number of floors.

waterfront: Whether the property has a waterfront view.

view: Rating of the property’s view.

condition: Condition of the property.

sqft_above: Square footage above ground level.

sqft_basement: Square footage of the basement.

# Features
1.Linear Regression Model:
Trained using scikit-learn’s LinearRegression class.
Predicts house prices based on selected features.

2.Data Visualization:
Scatter plot and best fit line for sqft_living vs. price.

3.Evaluation Metrics:
Mean Squared Error (MSE).
R-squared (R²) score.

# Usage
1.Load your dataset in CSV format.

2.Run the Python script to train the model and visualize the results.

3.View the output metrics and plots.

# Code Explanation
1.Linear Regression
The linear regression model is trained on the following features:
bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, view, condition, sqft_above, and sqft_basement.

2.Visualization
The scatter plot visualizes the relationship between sqft_living and price, with a best fit line representing the linear regression model.

3.Evaluation
MSE: Measures the average squared error between predicted and actual values.
R² Score: Indicates the proportion of variance explained by the model.

# Example Output
Evaluation Metrics:

Mean Squared Error (MSE): 990204087727.1417

R² Score: 0.029065410341410414

Visualization:
![linear regression](https://github.com/user-attachments/assets/6129e9c0-7e23-4163-9398-3d6df9446a9d)

For questions or suggestions, contact navyasrigude3@gmail.com.

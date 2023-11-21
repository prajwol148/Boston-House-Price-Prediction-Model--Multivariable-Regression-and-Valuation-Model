# Boston House Price Prediction Model

## Project Overview

This project revolves around building a robust Multivariable Regression model to predict house prices in Boston, Massachusetts during the 1970s. Using historical data, the model estimates prices based on various house characteristics like the number of rooms, proximity to employment centers, local wealth status, and student-to-teacher ratios in schools.

### Key Objectives:
1. Analyze and explore the Boston house price dataset.
2. Split data into training and testing sets.
3. Implement a Multivariable Regression model.
4. Evaluate model coefficients and residuals.
5. Improve model performance with data transformations.
6. Utilize the model for property price estimations.

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Seaborn, Plotly, Matplotlib, Scikit-learn

## Dataset
The dataset comprises 506 instances, with 13 numeric/categorical predictive attributes and the median value of owner-occupied homes as the target variable.

## Exploratory Data Analysis
Preliminary data exploration involved understanding the dataset's structure, identifying column names, and checking for null values or duplicates.

## Feature Visualization
Visualized key features like PRICE, RM (average number of rooms per dwelling), DIS (weighted distances to employment centers), and RAD (accessibility index to radial highways) using Seaborn's distribution plots and Kernel Density Estimates.

## Relationship Analysis
A pair plot was used to understand the relationships between various variables such as pollution levels, number of rooms, and house prices.

## Model Building and Evaluation
- **Data Splitting**: The data was split into training and testing sets (80/20) to evaluate the model on unseen data.
- **Model Formulation**: The Linear Regression model incorporated 13 features, forming a comprehensive approach to house valuation.
- **Model Training and Accuracy**: The model achieved an r-squared accuracy of approximately 75% on the training data.
- **Coefficient Evaluation**: Analyzed the impact of each feature on house prices, confirming the positive relationship between room numbers and price.
- **Residual Analysis**: Investigated the residuals to assess the prediction errors of the model.

## Data Transformation
To enhance the model's performance, experimented with data transformations such as log transformation of the target variable, 'PRICE', to reduce skewness and improve fit.

## Enhanced Model with Log Prices
A second regression model was implemented using log-transformed prices to compare and validate improvements over the initial model.

## Conclusion
The model provides robust housing price estimates on unseen data. It captures the positive and negative effects of neighborhood attributes like
school quality, employment access and poverty levels on property values. The business can use it to estimate returns on investments in future
development projects.

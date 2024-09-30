
## Housing Price Prediction Using Regression Models
## Project Overview

This project involves predicting housing prices based on real estate data using regression models. The dataset is sourced from Zillow’s real estate research, and the project implements a simple linear regression model to forecast housing prices for different regions in the United States.
## Dataset


The dataset is sourced from Zillow Research and contains monthly home values across various regions from 2000 to 2024. Key columns in the dataset include:

RegionName: The name of the city or metro area.
StateName: The state where the region is located.
SizeRank: A ranking of the size of the metro area.
2024-08-31: The housing price for August 2024, which serves as the target for our prediction model.

The full dataset can be downloaded from Zillow Research Data.

## Tech Stack

Python: Programming language used for the entire project.

Libraries:
pandas: For data manipulation and preprocessing.

scikit-learn: For building and training the regression model.

Matplotlib & Seaborn: For data visualization and feature importance analysis.

Jupyter Notebooks: For exploratory analysis and code development.# Model and Results

The project uses a Linear Regression model to predict housing prices. The features used for prediction include:

Region (encoded)
State (encoded)
SizeRank
Model Evaluation:
Root Mean Squared Error (RMSE): 137,089.37
R-squared (R²) Score: 0.0939
These results suggest that while the model captures some trends, there may be other important features not included in this simple model. Further improvements can be made by including more advanced models and additional data features.

# Visualizations:
Feature Importance: Shows the contribution of features like region, state, and size rank in predicting housing prices.
Actual vs Predicted Prices: A scatter plot comparing actual housing prices with predicted prices, providing insights into the model’s accuracy.
House Price Prediction using Linear Regression

Project Overview:
This project focuses on building a machine learning model to predict real estate prices based on various features like area type, location, square footage, and number of bathrooms. It uses supervised learning techniques to provide accurate price estimates for properties.

Key Steps Taken:

Data Exploration: Analyzed the dataset to understand the distribution of prices and the impact of different features.

Feature Engineering: Handled categorical data (like location and area type) using one-hot encoding and managed numerical features for better model performance.

Pre-processing: Applied Scaling (StandardScaler) and split the data into training and testing sets.

Model Development: Implemented a Linear Regression model to establish the relationship between independent variables and property prices.

Evaluation: Measured model performance using metrics such as R-squared (R2 Score) and Mean Absolute Error (MAE).

Technologies Used:

Python

Pandas & NumPy

Scikit-learn

Matplotlib & Seaborn

Dataset Features:
The model utilizes several key factors including:

Total Square Feet (sqft)

Number of Bedrooms (size)

Number of Bathrooms (bath)

Location and Area Type

Availability (Ready to move status)

How to Run:

Clone the repository.

Ensure you have the required libraries installed: pip install pandas scikit-learn seaborn matplotlib.

Open the Jupyter Notebook (project_intelligent.ipynb) and run the cells to see the data analysis and model predictions.

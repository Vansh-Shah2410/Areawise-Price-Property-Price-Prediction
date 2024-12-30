# Areawise-Property-Price-Prediction
**Overview**
-
This project aims to predict property prices based on the area using a simple linear regression model. The dataset includes information about various areas and their respective property prices. The objective is to understand the correlation between area and price, and to develop a predictive model for property prices.

**Project Structure**
-
* Data Loading and DataFrame Creation: The data is imported into a Pandas DataFrame from a CSV file hosted on GitHub.
* Data Visualization: A scatter plot is generated with Matplotlib to illustrate the relationship between area and property prices.
* Data Preprocessing: The dataset is already clean, so no additional preprocessing is required.
* Data Splitting: The dataset is separated into input (area) and output (price) variables.
* Model Training: A linear regression model is applied to the data using the scikit-learn library.
* Individual Prediction: The trained model is used to predict the price for a given area (2000 sqft).
* Model Evaluation: The predictions of the model are compared with the actual price values.
* Coefficients and Intercept: The model’s coefficients (slope) and intercept are extracted.
* Best Fit Line Visualization: A scatter plot of actual values is shown, with the best-fit line plotted using the linear regression model.

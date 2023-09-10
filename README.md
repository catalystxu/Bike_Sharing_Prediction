## Bike_Sharing_Prediction
### Overview
This project focuses on predicting bike rental quantities in Washington DC utilizing a machine learning approach. We built a predictive model using XGBoost based on over 20 variables. Our goal was to create a robust model that accurately forecasts bike rentals, allowing for better resource allocation and planning.

### Project Details
Date: February 2023  
Kaggle Competition: Achieved a top 10% rank in an in-class Kaggle competition.
### Key Steps
__Data Preprocessing__
* Missing Value Imputation: We used Ordinary Least Squares (OLS) to impute missing values in our dataset.

* Feature Transformation: To increase the robustness of our model, we applied various transformations to our data using __numpy__ in Python(for the R version, we use __tidyverse__ for all the data preprocessing)

__Feature Selection__
* Lasso Regression: We employed Lasso Regression to conduct feature selection. This helped us reduce noise in the dataset by eliminating multicollinearity and selecting the most relevant features for prediction.

__Model Building__
* Random Forest: we tried RF model and compared it with other approaches with RMSE
* XGBoost: Our predictive model eventually chose to use the __XGBoost__ algorithm, a powerful tool for regression tasks. It takes into account the selected features to predict bike rental quantities accurately.

### Contributors
Rita Xu  
Keyi Jiang  
Freya Wang  

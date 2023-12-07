# Bangladesh Real Estate Market Dataset Analysis

![House Price](house.png)

## Overview
This dataset offers a detailed collection of house listings from various cities and regions in Bangladesh, with a specific focus on Dhaka and Chittagong. It encompasses essential details such as location, property type, size, amenities, and pricing. The dataset is consistently updated to provide an accurate and current portrayal of the housing market in Bangladesh.

## Purpose
The dataset caters to diverse purposes, serving as a valuable resource for researchers, data scientists, real estate professionals, and investors. Some key use cases include:
- Analyzing regional price trends
- Identifying popular neighborhoods and amenities
- Training machine learning models for predicting housing prices

## Machine Learning Models
The following regression models have been applied to analyze and predict housing prices using this dataset:

1. **Linear Regression:**
   - A fundamental model assuming a linear relationship between input features and housing prices.

2. **XGBRegressor (Extreme Gradient Boosting):**
   - A powerful gradient boosting algorithm known for its speed and performance, applied specifically for regression tasks.

3. **LGBMRegressor (LightGBM):**
   - Another gradient boosting framework, recognized for efficiency and speed, utilized for regression on this dataset.
  
4. **Random Forest:**
   - A versatile ensemble learning model that leverages multiple decision trees to make predictions, often robust and effective for various datasets.

## Dataset Structure
The dataset is structured with the following columns:

- **Location:** The geographical location of the property.
- **Property Type:** Categorization of the property (e.g., apartment, house).
- **Size:** Size or area of the property.
- **Amenities:** Features and facilities associated with the property.
- **Price:** The listed price of the property.

## Preprocessing Steps
Before applying the regression models, the dataset underwent the following preprocessing steps:

1. **Handling Missing Data:**
   - Any missing data in crucial columns was addressed through imputation or removal.

2. **Encoding Categorical Variables:**
   - Categorical variables like "Property Type" were encoded to make them suitable for the regression models.

3. **Feature Scaling:**
   - To ensure consistent model performance, numerical features were scaled.

## How to Use
1. **Dataset Access:**
   - Download the dataset in [CSV format](https://github.com/SalehAhmedShafin/Analyzing-House-Price-in-Bangladesh/tree/master/Dataset) for your analysis.

2. **Run the Models:**
   - Explore the implementation of Linear Regression, Random Forest, XGBRegressor, and LGBMRegressor in the notebook [here](https://github.com/SalehAhmedShafin/Analyzing-House-Price-in-Bangladesh/tree/master/Code).

3. **Customization:**
   - Customize models or dataset features based on specific research questions or objectives.

## Potential Challenges
- **Heterogeneity:** The dataset may exhibit variations in property listings, requiring careful consideration during analysis.
- **Outliers:** Addressing outliers in pricing or property size may impact model performance.

## Contributing
If you encounter issues or have suggestions for improvement, please open an issue or submit a pull request.

Happy analyzing!

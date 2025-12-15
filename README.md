# House_Price_Prediction
This project analyzes and predicts house prices in Nigeria using real estate listing data. It covers data cleaning, exploratory data analysis, feature engineering, and the development of machine learning models, with a focus on comparing linear regression and XGBoost. 


Overall Descriptive Analysis of the Project

This project provides a comprehensive analysis of house prices in Nigeria using real estate listing data, with the goal of understanding key price drivers and building accurate predictive models. The dataset contains a mix of numerical and categorical features describing property characteristics such as location, size, amenities, and property type.

Exploratory Data Analysis revealed that house prices are highly skewed, with a small number of extremely expensive properties creating significant outliers. Log transformation and outlier handling were therefore necessary to stabilize the distribution and improve model performance. Location based analysis showed strong price differences across states and towns, confirming that location is one of the most influential factors in determining property value.

Size related features such as bedrooms, bathrooms, and toilets showed a positive but weak relationship with price, indicating diminishing returns beyond a certain point. This suggests that simply increasing the number of rooms does not guarantee higher property value without favorable location and property type. Correlation analysis further supported this, as room counts were more strongly correlated with each other than with price.

Feature engineering played a critical role in improving predictive power. Techniques such as log transformation, target encoding with smoothing, average price features, and price per bedroom helped capture non linear relationships and local pricing patterns. Model comparison showed that while linear regression performed reasonably well after cleaning and outlier removal, it struggled to capture complex interactions in the data.

The XGBoost model significantly outperformed linear regression, achieving near perfect predictive accuracy. Feature importance confirmed that engineered features and location-based variables contributed most to price prediction, validating the modeling approach.

Overall, the project successfully combines EDA, feature engineering, and advanced modeling to deliver both strong predictive performance and meaningful insights into the Nigerian housing market.

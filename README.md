# Airbnb Pricing Model

**Overview:**
In this project, a predictive model for Airbnb listing prices was developed, employing advanced data analytics and machine learning techniques. 
The analysis compared Linear Regression, Decision Tree, and Random Forest models with the goal of unraveling patterns and predicting listing prices.

**Dataset:**
The dataset comprises 8,528 rows and 36 variables, including 23 numeric and 13 character variables. The Dependent Variable (Price) exhibited a right-skewed distribution, prompting a log transformation to address skewness and outliers.
Transformation and categorization were applied to numeric variables to enhance analysis, and multicollinearity was assessed.

**Model Comparison:**
The dataset was split into TRAIN (80%) and TEST (20%) sets for model training and evaluation. The Linear Regression model emerged as the optimal choice, showcasing superior generalization on new, unseen data. 
Notably, variables like 'maximum nights' and 'rating' were excluded from the final model, indicating their insignificant influence on listing prices.

**Insights:**
Parameter estimates provided valuable insights. Listings with over 3 bathrooms, entire homes for rent, extra bedrooms, a higher number of guests, and those located in high-demand neighborhoods tended to command higher prices. 
In contrast, Decision Tree and Random Forests displayed potential overfitting with poor performance on the test data.

**Conclusion:**
The Linear Regression model, enriched by insights from the LASSO variable selection process, proves to be a reliable tool for predicting Airbnb listing prices. 
Its successful application on the test dataset affirms its generalization capabilities and underscores its practical utility for stakeholders in the Airbnb ecosystem.

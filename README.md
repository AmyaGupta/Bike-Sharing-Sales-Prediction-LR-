# Bike Sharing : Sales Prediction 

## Business Problem
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

We need to answer two questions for the company:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.

## Dataset
Dataset used is stored in day.csv file.

## DataCleaning and EDA
1. Checked for missing values and prformed data quality checks.
2. **Feature Engineering**: Created derived variables to better represent the data.
3. **Label Encoding**: Provided appropriate labels to the values wherever required.
4. **EDA**: Numerical and Categorical variables analysis.
5. **Dummy Variables**: Created dummies for Nominal Features.

## Fitting the model
1. Splitted the dataset into train and test data.
2. Applied **Scaling**: Normalized the numerical features.
3. Checked Correlations between different variables to get started with model building.
4. Used **Recursive Feature Elimination** to get top 15 most important variables.
5. Then, by iteratively checking the VIF and p-values for variables, dropped insignificant variables one by one to get the final linear regression model. **(Manual Elimination)**

## Results 
Interpreted the Final Results and proposed recommendations to provide better customer exoerience and boosting the business.

All the steps and results are explained along with python code in the jupiter notebook.

# Linear-Regression-on-Bike-Sharing-Dataset

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
3. Checking Correlations between different variables to get started with model building.
4. Used **Recursive Feature Elimination** to get top 15 most important variables.
5. Then, by iteratively checking the VIF and p-values for variables, dropped insignificant variables one by one to get the final linear regression model. **(Manual Elimination)**

## Results 
Interpreted the Final Results and proposed recommendations to provide better customer exoerience and boosting the business.

All of these steps and results are explained along with python code in the jupiter notebook.

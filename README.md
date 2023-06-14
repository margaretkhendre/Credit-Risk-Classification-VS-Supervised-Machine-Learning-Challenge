# Supervised Machine Learning Challenge

## Instructions

### Split the Data into Training and Testing Sets
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.
* Note that...A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

<img width="922" alt="Screenshot 2023-06-13 at 8 49 11 PM" src="https://github.com/margaretkhendre/Credit-Risk-Classification-VS-Supervised-Machine-Learning-Challenge/assets/121995835/ada0f2c9-22af-44cc-b6af-9b64a6b34150">

### Create a Logistic Regression Model with the Original Data
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
  - Calculate the accuracy score of the model.
  - Generate a confusion matrix.
  - Print the classification report.
  
<img width="922" alt="Screenshot 2023-06-13 at 8 50 00 PM" src="https://github.com/margaretkhendre/Credit-Risk-Classification-VS-Supervised-Machine-Learning-Challenge/assets/121995835/eb3efd03-e37e-4103-b1e3-7fb04671fe12">

### Predict a Logistic Regression Model with Resampled Data
1. Use the RandomOverSampler module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points.

<img width="771" alt="Screenshot 2023-06-13 at 8 52 31 PM" src="https://github.com/margaretkhendre/Credit-Risk-Classification-VS-Supervised-Machine-Learning-Challenge/assets/121995835/7d7320b8-4416-4e67-887e-ebac51f30ed1">

2. Use the LogisticRegression classifier and the resampled data to fit the model and make predictions.
3. Evaluate the model’s performance by doing the following:
  - Calculate the accuracy score of the model.
  - Generate a confusion matrix.
  - Print the classification report.
 
<img width="771" alt="Screenshot 2023-06-13 at 8 53 48 PM" src="https://github.com/margaretkhendre/Credit-Risk-Classification-VS-Supervised-Machine-Learning-Challenge/assets/121995835/95bc2e93-afc0-4341-85a1-a34e635991f3">


### Write a Credit Risk Analysis Report
Include:
1. **An overview of the analysis:** Explain the purpose of this analysis.
2. **The results:** Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. **A summary:** Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

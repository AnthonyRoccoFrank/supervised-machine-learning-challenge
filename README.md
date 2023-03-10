# Supervised Machine Learning Challenge

## Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

## Instructions

### Retrieve the Data
The data is located in the Challenge Files Folder: 
<code>lending_data.csv</code>

Import the data using Pandas. Display the resulting dataframe to confirm the import was successful.

### Predict Model Performance
You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct!

Write down your prediction in the designated cells in your Jupyter Notebook, and provide justification for your educated guess.

### Split the Data into Training and Testing Sets
Create the features DataFrame, <code>X</code>, by removing the <code>loan_status</code> column. Create <code>y</code>, the labels set, by using the <code>loan_status</code> column. Split the data into training and testing datasets by using the <code>train_test_split</code> function.

### Create, Fit and Compare Models
Create a Logistic Regression model, fit it to the training data that you created in the previous step. Then, determine the model's score by using the <code>score</code> function and the testing data from the previous step. Do the same for a Random Forest Classifier. You may choose any starting hyperparameters you like.

Review the scores of each model. Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the designated markdown cell.


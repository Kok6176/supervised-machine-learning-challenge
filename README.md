# supervised-machine-learning-challenge
This is kokila's Supervised ML challenge

## Retrieve the Data
The data is located in the Challenge Files Folder:
* `lending_data.csv`
Import the data using Pandas. Display the resulting dataframe to confirm the import was successful.

## Predict Model Performance
You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! 

* I am predicting that a random forest produces good predictions that can be understood easily. It can handle large datasets efficiently. The random forest algorithm provides a higher level of accuracy in predicting outcomes over the decision tree algorithm.*

## Split the Data into Training and Testing Sets
Split the data into X_train, X_test, and y_train, y_test.

## Create, Fit and Compare Models
Create a Logistic Regression model, fit it to the data, and print the model's score. Do the same for a Random Forest Classifier. You may choose any starting hyperparameters you like. 

* My conclusion is RandomForestClassifier will perform better than the Logistic Regression Model. The above training and fitting the data in both models support my prediction. For additional confirmation, I executed Logistic Regression in both regular and StandardScalar method. *
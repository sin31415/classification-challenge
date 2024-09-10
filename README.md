# classification-challenge
A machine learning project that uses classification to attempt to accurately detect spam emails so it can filter them out of its customers' inboxes.


Split the Data into Training and Testing Sets 
* There is a prediction about which model is expected to do better.

* The labels set (y) is created from the “spam” column.

* The features DataFrame (X) is created from the remaining columns.

* The value_counts function is used to check the balance of the labels variable (y).

* The data is correctly split into training and testing datasets by using train_test_split. 

Scale the Features 
* An instance of StandardScaler is created.

* The Standard Scaler instance is fit with the training data.

* The training features DataFrame is scaled using the transform function.

* The testing features DataFrame is scaled using the transform function.

Logistic Regression Model 
* A logistic regression model is created with a random_state of 1.

* The logistic regression model is fitted to the scaled training data (X_train_scaled and y_train).

* Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable.

* The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function.

Random Forest Model 
* A random forest model is created with a random_state of 1.

* The random forest model is fitted to the scaled training data (X_train_scaled and y_train).

* Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable.

* The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function.

The models are evaluated.
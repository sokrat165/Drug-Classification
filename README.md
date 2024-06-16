# Drug-Classification
Data Preparation: You split the data into input variables (X) and the target variable (y). You applied StandardScaler to scale X for training.

Data Splitting: Utilized train_test_split to divide the data into training and testing sets (X_train, X_test, y_train, y_test).

Statistical Analysis: Employed KFold for cross-validation and used cross_val_score and cross_val_predict to obtain model predictions and evaluate performance.

Modeling and Evaluation: Constructed a Multinomial Logistic Regression model (LogisticRegression) and used cross_validate to assess performance metrics like accuracy, precision, recall, and F1-score.

Probability Calculation: Calculated probabilities using log_likelihood indices and chi-squared to evaluate the model's significance.

Classification Report: Lastly, printed a classification_report to illustrate the model's performance on the training data, including precision, recall, and F1-score for each class.

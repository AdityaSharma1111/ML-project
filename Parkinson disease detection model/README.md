# ML-project
Parkinson Disease Detection Model

This project implements machine learning algorithms to detect Parkinson's disease using features extracted from voice recordings. The primary goal is to provide a tool that can accurately classify whether a person has Parkinson's disease based on the given features.

Algorithms Implemented:-
1. Logistic Regression
The Logistic Regression model is implemented from scratch without using any machine learning libraries. The implementation includes:
- Initialization of parameters.
- Iterative weight updates using gradient descent.
- Sigmoid function for prediction.
- Binary classification based on a threshold of 0.5.
2. Random Forest
The Random Forest model uses the `DecisionTreeClassifier` from `sklearn`. The implementation includes:
- Bootstrapping to create random subsets of the training data.
- Training multiple decision trees on these subsets.
- Combining predictions from individual trees using majority voting.

Dataset
The project uses two datasets: a training dataset (`data_train.csv`) and a testing dataset (`data_test.csv`). Each dataset contains features extracted from voice recordings, which are used to train and evaluate the models.

Results
The accuracy of the Random Forest model on the test data is printed as a percentage. You can uncomment the Logistic Regression model lines to train and evaluate it instead of the Random Forest model.

Conclusion
This project demonstrates the use of Logistic Regression and Random Forest models for detecting Parkinson's disease. The Random Forest model is used by default, but the Logistic Regression model can also be easily tested by uncommenting the respective lines in the code. The accuracy of the models on the test dataset provides an indication of their performance.

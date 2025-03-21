# NoBroker-Hyderabad-Housing-Data-Analysis
NoBroker's Housing Data Analysis
THis project uses NoBrokers Housing Data from its website for the city of Hyderabad and to build a regression model for price prediction system.

Based on the regression model comparison analysis for Hyderabad housing data, here are some key observations:

Linear Regression has a high training accuracy (0.797732) but a testing accuracy of 0.000, indicating severe overfitting or a possible issue in implementation.
Ridge (0.780074) and Lasso (0.779326) perform similarly on testing data, suggesting regularization helps but might not be significantly improving the model.
SVM (0.665076) has the lowest training accuracy (0.649035) but generalizes slightly better than Decision Tree.
Decision Tree (0.899493 training, 0.647585 testing) is highly overfitting.
Random Forest (0.965751 training, 0.780525 testing) shows strong generalization but is slightly behind Gradient Boosting.
Gradient Boosting (0.786066 testing accuracy) performs the best among all models.
XGBoost (0.960477 training, 0.773496 testing) is slightly behind Gradient Boosting, possibly due to hyperparameter tuning.
Perceptron (0.807858 training, 0.805392 testing) surprisingly generalizes well, showing that it might be useful in this dataset.
Best Model Choice:
Gradient Boosting (0.786066) has the highest testing accuracy, making it the best model.
Perceptron (0.805392) also performs well and is worth further exploration.
Random Forest (0.780525) is another strong contender.

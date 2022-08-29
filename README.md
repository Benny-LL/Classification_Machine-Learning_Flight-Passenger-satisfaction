# Classification_Machine-Learning_Flight-Passenger-satisfaction

My groupmates and I worked on this project to anticipate the satisfaction level of flight passenger by creating and testing different classification models from scikit-learn.

In the code, we went through the below processes:
- Pre-processing: filled in the missing data and adopted one-hot encoding for the dimensions with text data, then we had 22 dimensions in the data set
- Splited the data set into training sets and testing sets as 75:25, so that we had X_train. X_test, y_train, and y_test
- Standardized the data (X_train and X_test) with Standard Scaler
- Resampled the imbalance data with Smote and Smoteenn
- Tried multiple classifier models from sklearn: KNeighbors, DecisionTree, RandomForest, GaussianNB, SVC, LogisticRegression (RandomForest resutled the highest accuracy)
- Dimensionality reduction for >80% accuracy through Principal Component Analysis (6 or 10 components were more efficient)
- Hyper Parameter Optimization with RaandomizedSearchCV to get the best combination of hyper parameters (saved around 20 hours)

More details are in the pdf file "Flight Passenger Satisfaction machine learning project".

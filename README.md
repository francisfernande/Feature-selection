# Feature-selection

In which order should u do the feature selection steps?

0. Clean the dataset, get rid of NaN and junk values. Check format for datatypes in testset etc

1. Use z-method to eliminate outliers 

2. Normalize the train_X data

3. Check correlation between x_train variables and y_train. Drop variables that have a low correlation with the target variable.

4. Use pearsons correlation test to drop highly correlated variables from x_test 

5. Use variance threshold method to drop x_train variables with low variance. 

All variables that have been removed from the x_train data should be removed from the x_test aswell.

6. Fit x_train and y_ train to a classification model

7. Predict y(x_test)

8. Compare the predicted y(x_test) output with y_test to calculate accuracy

9. Try different classification models and see which one performs the best (have the highest accuracy)

Is this the right order?  Have I missed something?


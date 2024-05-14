# Model_Performance_testing_and_Hyper_parameter_tuning.
K-fold for 'model-performance' and Grid_search for 'hyper_parameter_tuning'.

* Breif:
* K-fold.
  - K-fold cross-validation is used for assessing the performance of a machine learning model to test the model on n folds we provide to check and have clear view for the future new data_set 
 whether it will bahave same as it on train and testing data_set.
  - it gives accuracy count on how many folds we have given and also average of all the accuracy for variance between each fold #fold = no of tests.
  - Once we have model performance by k-fold tools we can move with Grid-search.
* Grid-search.
  - Grid search is a hyperparameter tuning technique used to find the optimal combination of hyperparameters for a machine learning model.
  - here we try different combination of parameter for a model to find the best parameters for our model.

* Result:

 *K-fold 
   -With confusion matrix we have the accuracy of our model that is
  [[64  4]
   [ 3 29]]
  0.93
  - After Applying k-Fold Cross Validation
    Accuracy: 90.33 %
Standard Deviation: 6.57 %
  here the accuracy is the average of all fold results and standard deviation is the variance between each fold result accuracy.

 *Grid search
    - Applying Grid Search to find the best model and the best parameters.
    - best suitable hyper parameters for our trained model is
      Best Accuracy: 90.67 %
Best Parameters: {'C': 0.5, 'gamma': 0.6, 'kernel': 'rbf'}
    - by this we can notice that our model accuracy is increased from 90.33 to 90.67.


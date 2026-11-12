Elda's Entry:

The steps in Part 2 helped understand why the scaler and encoder need to be fitted on the training data, then transform the test data with the settings. The test accuracy gave 82.68% and that is what is used as the base line for the groups. Question 4 helped understand one pipeline helps keep preprocessin and prediction


Xinyu's Entry:

This lab helped us to see how Pipelines can be used to make a developer’s life easier to implement a model for developing in parts. The Part 3 implementation first a ColumnTransformer was implemented that applies different transformations for numeric and for categorical features. Then a Pipeline was created using make_pipeline that first applies the chosen transformations for the features and then the Random Forest Classifier.

Upon comparing the results of the Pipeline Method and the results of the Manual Method, I found that both methods reached an accuracy of 82.68%. It seems that using a Pipeline does not necessarily increase the model’s accuracy, but it organizes the steps of model development in a clean and efficient manner. It also helps to avoid forgetting important steps of data preparation and thus prevents data leakage by fitting all transformers on the training data before the estimator.

Through the creation of a Machine Learning Pipeline, I have seen how different elements of a model can be combined into one consistent workflow to aid in the management of code in machine learning projects to be easily maintained, reproduced, and reused.

# python_datascience

These are the projects I did while learning the different models of Machine Learning using python. 
All of the projects use publically availible dataset and are being guided by my learning through dataquest.io

1. Predicting Car prices using the K nearest neighbors regression model.
  This model uses a cars dataset availible at:
  description of dataset : https://archive.ics.uci.edu/ml/datasets/automobile
  dataset : https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data
  
  Steps taken show case examining dataset, cleanings and selecting features and target to predict.
  
  Running a univariate model for all selected features with k set at 5
  adding grid search to find best value for the hyperparameter k
  
  Using results from the univariate run to select best 2,3,4 and five features to run the model with using K=5
  then again using grid search to find best value for K for best 3 multivariate model runs
  
  Some ideas for next steps:

  Modify the knn_train_test() function to use k-fold cross validation instead of test/train validation.
  Modify the knn_train_test() function to perform the data cleaning as well.
 
 
2. Predicting House Prices using the Linear regression model
   This dataset is availible inb the respository. Description of dataset can be found at: 
   https://s3.amazonaws.com/dq-content/307/data_description.txt  
  
   focuses on Featuring Engineers and using different methods to validate the model results.
   Built in a iterative way where feature engineering expriment is done and then the functions are modified to bring in what  works.
   
   
  

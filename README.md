# AI-FinalProject

**Abstract: ** The purpose of this project is to perform a Regression Task and determine the most suitable model to use on the White Wine Quality Data Set, with ‘alcohol’ being the target vector. This project was realized through the PyCaret Library following their “Regression Tutorial (REG101) – Level Beginner” in Google Colab. Some of the preliminary steps needed for this project were importing the dataset and setting up the PyCaret library into Colab. Once done, the library takes all the heavy lifting off you as it evaluates several models for the dataset provided using its compare_models function. The compare_model function evaluates all models using k-cross validation for metric evaluation (10 by default). It then ranks the best model to use for a given dataset based on given metrics, for Regression these would be MAE, MSE, RMSE, R2, RMSLE, MAPE. In this case the best Model to use for the white wine dataset is Light Gradient Boosting Machine (lightgbm) model. 

Prior to tuning the model mean scores: MAE: 0.2491, MSE: 0.1151, RMSE: 0.3378, R2: 0.9231, RMSLE: 0.0291, MAPE: 0.0237.

After tuning the model mean scores: MAE: 0.2288 MSE: 0.1093, RMSE: 0.3288, R2: 0.9270, RMSLE: 0.0282, MAPE: 0.0237.

Prediction of the model on Test/Hold-Out Sample mean scores: MAE: 0.2128 MSE: 0.0925, RMSE: 0.3041, R2: 0.938, RMSLE: 0.0262, MAPE: 0.0202.

It appears that the most important feature to determine the target vector (‘alcohol’) is residual sugar followed by density as a close second.

It has a 0.9465 R2 score in predicting unseen data. 


Video Link: https://youtu.be/E4Kj5a_DcWc

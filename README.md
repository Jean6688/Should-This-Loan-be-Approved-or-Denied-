# Should-This-Loan-be-Approved-or-Denied-
To predict the small business loan should be approved or denied. I had 9 models to predict the loan status. The best model I found is Radom Forest. The top two most important predictors are Charged-Off Amount and Term.

## Analysis Summary

* Analysis Matric

When I look into the prediction results, the most important matric I was looking for is recall rate. My emphasis is to see the charged-off loans that has not been predicted rightly, which is the smaller the better. This could be calculated by the formular (1- recall rate). In another word, I was looking for the biggest recall rate.

* Cross Validation

I also checked if the models are overfitting. As the recall rate, accuracy rate is very high, this may result from overfitting. I used cross validation to test the overfitting. Cross validation could give an insight on how well the prediction model perform with unknow dataset (Wikipedia). The average accuracy rates of cross validation are almost the same with the prediction accuracy rate.

* Feature Importance

The important feature shows how important the features when predict the default status.

# Real-Estate-Price-Prediction
This project used the real estate price data from Taiwan to predict the prices using Machine Learning in R


Abstract: This study focused on employing various data-mining algorithm to predict the sale price/unit area of a house. Using a 10-fold cross validation framework, predictive ability of Multiple Linear Regression, Lasso regression, Ridge Regression and Gradient Boosted Regression models was assessed to predict the sale price/unit area of houses in Sindian District, New Taipei City, Taiwan. We found that Gradient Boosted Regression performs better than the other models with RMSE and R-Squared scores of 5.472276 and 0.8077778 respectively![image](https://user-images.githubusercontent.com/113776928/190859552-93d07dac-1717-4dd7-992e-ddea60d3d6b3.png)


Model performance: 

Using all predictors as the independent variable to measure their relationship with the price/unit area of a house and using RMSE and R Squared as performance measures, we found following results for each model: 

Model	                          RMSE    	R-Squared
OLS Multiple Linear Regression	7.275663	0.6649279
Lasso Regression	              7.247109	0.6651423
Ridge Regression	              7.224989	0.6656627
Gradient Boosted Regression	    5.472276	0.8077778


It is observed that OLS linear regression resulted in the highest RMSE and lowest R-Squared rate, which shows that this was the least performing model. Lasso Regression showed the RMSE of 7.247109 with R-Squared score of 0.6651423. Ridge Regression showed the RMSE score of 7.224989 with R Squared of 0.6656627, which shows better performance as compared to the LASSO Regression model and OLS Linear Regression model. The best performance was seen by Gradient Boosted Regression model as it yielded an RMSE score of 5.42276, which is the lowest out of all the other models and the highest R-Squared score of 0.8077778. 
![image](https://user-images.githubusercontent.com/113776928/190859569-d622868f-ccd9-4aaf-984c-cde60e917ca1.png)


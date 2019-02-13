# AltaML Assessment
## Farming data analysis report

For a farming company, I would like to help them to earn more profit. So the most relevant parameter will be the yield which is the income for them. Under this situation, I chose yield as the target value and used a linear model to do the prediction.

According to the correlation heatmap provided in the program, it can be clearly said that the target value(yield) is related to "area" and "fertilizer_usage". So based on this, I divided the whole dataset into 60% traning data and 40% test data to fit and test the model.

As for the model choise, I used diffenrent kinds of linear models as you can find in the program. After compare the RMSE and coefficient of determination R^2, the linear regression model is the best with a RMSE = 16.97554 and R^2 = 0.55561. So the graph and corresponding paramters are shown in the program.

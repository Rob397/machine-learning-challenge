# machine-learning-challenge
machine-learning homework


# A comparison of each model's performance as well as a summary about findings and any assumptions. 

This task is about determining if a new set of data can be classified as a plant. Thus classification models were investigated  and different kernels were used to determine what the best fitting model was for the model types chosen. I chose to use a sequential model, SVC model and finally a logistic model. The first model I chose was sequential and this did the best in my opinion by looking at the accruacy for each epoc. The SVC approach was also accurate but the score was more inconsistent when looking at each epoc perfomance data. Both model1 and model2 provided the best results for parameters  {'C': 10, 'gamma': 0.0001, 'kernel': 'linear'} resulting in 0.8714 accuracy . Each of these models was provided with linear, polynomial and radial basis function as kernel options in the model tuning process but linear was still the best. A simple kernel was the best. My logistic funciton still needs adjusting for the scaled data, it would have been good to see how the Support Vector Machine model compares with the logistic regression. If I had more time, I might have changed the number of epocs to see how each model improves with more iterations. 

In conclusion, the sequential model with the GridSearch tuning was the best model. 
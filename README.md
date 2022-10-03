# machine-learning-challenge
machine-learning homework


# A comparison of each model's performance as well as a summary about findings and any assumptions. 

This task is about determining if a new set of data can be classified as a planet. Thus classification models were investigated  and different kernels were used to determine what the best fitting model was for the model types chosen. I chose to use a sequential model, SVC model and finally a logistic model. The first model I chose was sequential and this did the best in my opinion by looking at the accruacy for each epoc. The SVC approach was also accurate but the score was more inconsistent when looking at each epoc perfomance data. Both model1 and model2 provided the best results for parameters  {'C': 10, 'gamma': 0.0001, 'kernel': 'linear'} resulting in 0.8714 accuracy . Each of these models was provided with linear, polynomial and radial basis function as kernel options in the model tuning process but linear was still the best. A simple kernel was the best. The logistic model has Training Data Score of 0.8899 and a Testing Data Score of 0.8850. The was slightly better however the data was not scaled and I wonder what the consequences of that are when comparing it to the Support Vector Machine model. 


The first ten predictions from the logistic model don't look very reliable. 
In conclusion, the sequential model with the GridSearch tuning was the best model and quite reliable. 
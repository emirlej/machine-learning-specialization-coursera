### Q1: Which of the following is NOT a valid measure of overfitting?
Answer: Sum of parameters (w1+w2+...+wn)

### Q2: In ridge regression, choosing a large penalty strength λ tends to lead to a model with (choose all that apply):
Answer:
- High Bias
- Low Variance

### Q3: Which of the following plots best characterize the trend of bias, variance, and generalization error (all plotted over λ)?
Answer: Figure 3

### Q4: In ridge regression using unnormalized features, if you double the value of a given feature (i.e., a specific column of the feature matrix), what happens to the estimated coefficients for every other feature? They:
Answer: Stay the same (wrong), Impossible to tell from the information provided

### Q5: If we only have a small number of observations, K-fold cross validation provides a better estimate of the generalization error than the validation set method.
Answer: True

### Q6: 10-fold cross validation is more computationally intensive than leave-one-out (LOO) cross validation.
Answer: False

### Q7: 
Assume you have a training dataset consisting of N observations and D features. You use the closed-form solution to fit a multiple linear regression model using ridge regression. To choose the penalty strength λ, you run leave-one-out (LOO) cross validation searching over L values of λ. Let Cost(N,D) be the computational cost of running ridge regression with N data points and D features. Assume the prediction cost is negligible compared to the computational cost of training the model. Which of the following represents the computational cost of your LOO cross validation procedure?

Answer: L⋅Cost(N,D) (wrong), LN⋅Cost(N,D) (wrong)

### Q8: 
Assume you have a training dataset consisting of 1 million observations. Suppose running the closed-form solution to fit a multiple linear regression model using ridge regression on this data takes 1 second. Suppose you want to choose the penalty strength λ by searching over 100 possible values. How long will it take to run leave-one-out (LOO) cross-validation for this selection task?

Answer: About 3 days (wrong), About 3 years

### Q9:
Assume you have a training dataset consisting of 1 million observations. Suppose running the closed-form solution to fit a multiple linear regression model using ridge regression on this data takes 1 second. Suppose you want to choose the penalty strength λ by searching over 100 possible values. If you only want to spend about 1 hour to select λ, what value of k should you use for k-fold cross-validation?

Answer: k=36


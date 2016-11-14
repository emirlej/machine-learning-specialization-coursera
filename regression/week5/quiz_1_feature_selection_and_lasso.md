### Q1: The best fit model of size 5 (i.e., with 5 features) always contains the set of features from best fit model of size 4.
Answer: False

### Q2: Given 20 potential features, how many models do you have to evaluate in the all subsets algorithm?
Answer: 1048576 (2**D)

### Q3: Given 20 potential features, how many models do you have to evaluate if you are running the forward stepwise greedy algorithm? Assume you run the algorithm all the way to the full feature set.
Answer: n+(n-1)+(n-2)...+ 1 = n*(n+1)/2 --> 210

### Q4: Which of the plots could correspond to a lasso coefficient path? Select ALL that apply.
Answer: Second plot and third plot

### Q5: Which of the following statements about coordinate descent is true? (Select all that apply.)
Answer: (False)
- A small enough step size should be chosen to guarantee convergence.
- To test the convergence of coordinate descent, look at the size of the maximum step you take as you cycle through coordinates.
- 

### Q6: Using normalized features, the ordinary least squares coordinate descent update for feature j has the form (with ρj defined as in the videos):
Answer: wj=ρj

### Q7: Using normalized features, the ridge regression coordinate descent update for feature j has the form (with ρj defined as in the videos):
Answer: w^j=ρj/(λ+1)

# Regularization
L1,L2

Reading

- ISLR: Pages 203-227. 
- Logistic Regression PDF attached. 


**Challenge**

Apply the logistic Regression to the banking dataset (data description here: https://archive.ics.uci.edu/ml/datasets/bank+marketing)

Also do the following:

- Check for missing data
- Data Exploration (write down your ideas for important variables BEFORE modelling)
- Create a base model using: Use statsmodels.discrete model to fit and get model.summary()
- Post fitting a base model, look at the summary, apply tests of collinearity etc. to come up with a candidate list of irrelevant variables
- Try dropping those variables and see if their is an improvement over the base model
- Standardize data
- Set the above models and aside and fit the data using LogisticRegression with both l1 and l2 penalty (via sklearn) and tune for the best value of C (check out the dupont_3 notebook for this). 


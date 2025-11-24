I would like to briefly discuss the problem statement of this project. 

Here we have the data from a debt collection company and based on the given data we have to find whether the debts can be recovered or not. 
And to achieve this we have to consider the statute-barred status for the given loan accounts. If the statute-barred status for an account 
is "Yes", then most probably the debt cannot be recovered and if it is "No", then there are high chances that the debt can be recoverd. That is the basic idea.

Next we will look into what is the goal that we are trying to achieve through this project. So, we have to develop a machine learning model 
which will be trained on the given data and it will predict the statute-barred status for the unseen data. And we have to check whether the 
predictions are accurate or not. So, this is basically a binary classification problem since there are only two outcomes 'Yes' or 'No'.

Now, let's see why is it important to predict the statute-barred status correctly. Let's try to understand what statute-barred actually means. 
A debt is considered statute-barred when the lender has crossed the time-limit to take certain legal actions to collect the debt. This means that 
the debt cannot be enforced by the court anymore. But this doesn't mean that the debt no longer exists. In some cases, the creditor or a debt collection 
agency may still try to collect the debt by using some other means.Therefore, by predicting the statute-barred status correctly, the debt collection 
agency can get a better understanding that what kind of action needs to be taken to recover the debts.

Hence, we will analyze the data and develop an approach to create the best possible machine learning model which could predict the statute-barred status correctly.

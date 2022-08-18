# Loan_Default_Predictor
Take a look at the simulated input loan data. Each row corresponds to a loan. It includes the borrower's demographics, income, education, etc. It also includes how many days the loan is overdue: ie, the maxoverduedays column. If maxoverduedays >90, we say that the borrower has defaulted on the loan.  Our objective is to write an algorithm so that given a new loan, we can predict whether it will default or not. Random Forest was deployed with 94% accuracy. A front end program was written for bank teller to consult on whether to approve a loan based on the borrower's profile. 


## Module 1 cleans and engineers features for predictive analysis
## Module 2 preprocess the data and trains the models
## Module 3 allows the bank teller to insert the borrower's profile and recommend if the loan should be approved

* Note 1 : as the data set, please find the dataset in this link: https://drive.google.com/file/d/1m777msHIPejhUWm7b34xOv_9cYPdJ95U/view?usp=sharing
* Note 2: The exported random forest model is 1GB. I recommend running module 2 on your local computer to export the model in order to run module 3 

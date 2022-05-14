# CREDIT-CARD-DEFAULT-PREDICTION
This Project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management , the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification – credible or not credible clients. The main objective of this project is to predict whether the customers will default or not in future period of time.
Important points:-
1.	Dataset consists of 30000 observations and 25 features in which there are 3 categorical features ‘SEX’ , ‘ EDUCATION’ ‘ MARITAL STATUS’ and the rest are numerical features.

2.	All the features were of integer type in our dataset.

3.	There are no null values nor any duplicate values.

4.	There are more females as compared to males in our dataset.

5.	By plotting the distribution plot categorical feature ‘EDUCATION’ and ‘MARRIAGE’ we get to see that there were more university customers and more single customers in our dataset.

6.	There is no correlation between bill amount and total month of delay.

7.	Customers with high credit limits tend to have higher ‘No-Default’ rate.

8.	Using the count plot, we get to know that there are less non-defaulters as compared to defaulters in our dataset.

9.	When Repayment scale = 0 is the most frequent observation in our dataset.

10.	For AGE = 29 there are more numbers of non-defaulters and for AGE = 21 and after 59 there are least defaulters in our dataset.

11.	PAY_0 / PAY_1 has most variable importance.

12.	We have used a heat map plot to get to know the correlation between Dependent and Independent variables. 

Final Conclusion:-  
  1.	We apply Logistic Regression, Random Forest Classifier , Gaussian NB Classifier and Linear SVC on our dataset we get to know Random Forest Classifier performs best (Because of high precision and low recall value) as compared to other models whereas the Gaussian NB performs bad (Because of low precision and high recall) for all scaling and sampling techniques.
  2.	After Random Forest Classifier Logistic Regression performs second best on our dataset with high precision and low recall.

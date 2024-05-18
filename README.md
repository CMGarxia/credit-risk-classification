# credit-risk-classification
This challange was completed with support from teaching staff, learning assistants, peers, AI, in class activities, and stack overflow. 
## Overview Analysis 
* The objective of building a supervised learning model was to assess if loan applicants are creditworthy. Using a Logistic Regression Model, we trained and tested the model using subsets of the original dataset. The dataset was divided into 'x' and 'y' components, with 'y' representing the loan status (0 for healthy, 1 for risky). 'x' contained independent variables like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.
* The model learned from a portion of the data (x_train and y_train) to make predictions. It was then tested using another part of the data (x_test) to see how well it could predict outcomes (y).

## Results 

The Logistical Regression Model was precise when predictiing outcomes of (0) Healthy and (1) Risky.
* The precision for healthy loan applicants was perfect at 100%, while for risky applicants, it was slightly lower.

* Recall for healthy applicants was also perfect at 100%.

* The weighted combination of precision and recall (F1 score) was 100% for healthy applicants and 91% for risky applicants.
  
The logistic regression model performed really well in predicting healthy loan status, achieving perfect precision and recall scores of 100%. However, it performed slightly worse in predicting risky loan status. The model's accuracy was very precise, particularly in predicting healthy loan status. The Logistical Regression is a better fit for this analysis. 

**Overview**  
The analysis is to train a Logistic Regression model to predict whether a loan is healthy or high risk based on 7 factors:
<ol>
  <li>loan_size</li>
  <li>interest_rate</li>
  <li>borrower_income</li>
  <li>debt_to_income</li>
  <li>num_of_accounts</li>
  <li>derogatory_marks</li>
  <li>total_debt</li>
</ol>  

**Results**  
We found the model has
<ul>
  <li>precision of 1.00 and recall of 0.99 for healthy loan</li>
  <li>precision of 0.85 and recall of 0.91 for high risk loan</li>
  <li>overall accuracy of 0.99</li>
</ul>

**Summary**  
The above result is based on a testing data of 18,765 healthy loans and 619 high risk loans, which is considerable. As the model has a high accuracy (99%), we would recommend the model to the company as it would mitigate the risk from high risk loans. 

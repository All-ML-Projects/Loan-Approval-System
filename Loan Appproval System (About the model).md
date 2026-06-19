#### Loan Appproval System (About the model)



###### Steps followed :

1\. import data

2\. drop all rows where target is null

3\. drop applicant id, gender column

4\. split data into X and y

5\. split train test data

6\. now to fill null values import imputer

&#x20;    the imputer should be use separately for train data and test data, to prevent data leakage



7\. X\_train, X\_test scaled separately

8\. features encoding 

&#x20;    risk mapping --> Loan\_Purpose, Education\_Level

&#x20;    one hot encoding --> Employment\_Status, maritial status, property area, employer category

&#x20;    label encoding ..> y\_train, y\_test (converting into numeric form)

9\. model training, prediction and evaluation metrics



Step 9 for all 3 models (Logistic Regression, Naive Bayes, KNN)







###### **Conclusion** --> Logistic and Naive bayes give good results. But in naive bayes, precision and recall are not balanced.



**So Logistic regression is best suited for this project.**





**Note** : Our primary evaluation metrics for this project is precision\_score and recall score.


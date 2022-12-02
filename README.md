# Online-Fraud-Detection-
Introduction¶
Fraud detection is a set of processes and analyses that allow businesses to identify and prevent unauthorized financial activity. In this project, we are working with Blossom Bank dataset, which is known as BB PLC and is a multinational financial services group, that offers retail and investment banking, pension management, asset management and payments services, headquartered in London, UK.

Problem statement
Because so many clients use online banking, fraud involving online transactions has long been a problem for banks and other financial institutions. In this project, Blossom Bank has to build machine learning model to predict online payment fraud.

Features in the Dataset¶
step: represents a unit of time where 1 step equals 1hour

type: type of online transaction

amount: the amount of the transaction
nameOrig: customer starting the transaction
oldbalanceOrg: balance before the transaction
newbalanceOrig: balance after the transaction
nameDest: recipient of the transaction
oldbalanceDest: initial balance of recipient before the transaction
newbalanceDest: the new balance of the recipient after the transaction
isFraud: fraud transaction


Discussion¶
After evaluating the exploratory data, it is evident that the Blossom Bank dataset is unbalanced, with a Not-Fraud rate of 99.9% and a Fraud rate of 0.1%.

Logistic Regression, K Neighbors, Decision Tree, and Random Forest have accuracy scores of 0.9986, 0.9993, 0.9996, and 0.9997, respectively. Because the accuracy rating is the same. As a result, accuracy is not an appropriate criteria for determining which model works best. When compared to the other models employed in this project, Random Forest has the highest precision of 95% and recall of 81%. The recall of the decision tree is 81%. It is therefore necessary to check further the f1 scores for each model. With an f1 score of 87%, Random Forest had the best performance, followed by Decision Tree with an f1 score of 83%. In Logistics Regression and KNeighbor, the percentages for F1 scores were very low.

Conclusion
It is clear that the F1 score is useful when dealing with an unbalanced dataset. As a result, the Random Forest model with an F1 score of 88% performed the best in assisting Blossom Bank in identifying fraudulent online transactions. Therefore, Blossom Bank should be more focused with improving True Positives performance.



# Bank-Marketing-Effectiveness-Prediction-Project- Classification

## Project Summary

This project aims to predict the effectiveness of a Portuguese banking institution's direct marketing campaigns through phone calls. The objective of these campaigns was to sell a bank term deposit product to clients. The success of the campaign was determined by whether the client subscribed to the product or not, which is represented by the binary variable "y" (YES or NO).

The data includes information on the number of contacts made to each client and other relevant features. The project will involve analyzing the data to classify whether a client will subscribe to the term deposit product or not. This analysis will provide valuable insights into the bank's marketing strategy and inform future campaign efforts. The results of the analysis will help the bank optimize its marketing efforts and increase its chances of success in selling its products to clients.

## Dataset Information

Number of instances: 45,211

Number of attributes: 17

## ***Features information***:

* **Age**: Numeric

* **job**: type of job

* **marital**: categorical :  [divorced,married,single,unknown]

* **education**: categorical  :  [illiterate,university degrees,unknown]

* **default**: has credit in default?  [Yes/No]

* **housing**: has housing loan?  [Yes/No]

* **loan**: has personal loan? [Yes/No]

* **contact**: contact communication type  [cellualr,telephone]

* **month**: last contact month of the year [jan to dec]

* **day_of_week**: last contact day of the week [mon to fri]

* **duration**: last conatct duration in seconds.

* **campaign**: number of contact performed before the campaign and for this client.

* **pdays**: number of days the passed by after the client was contacted from a previous campaign.

* **previous**: number of contact performed before this campaign and for this client.

* **poutcome**: outcome of the previous marketing campaign [failure,success,unknown]

## ***Target Variable*** :

* **y**: Has the client subscribed to term deposit?  [Yes/No]


## Libraries :

pandas

matplotlib

seaborn

scikit-learn

Algorithms

Logistic Regression

KNN

Naive Bayes

Random Forest

XGBoost

## So for final prediction we choosed KNearest Neighbour as best model.

## Its giving us the best result compare to other models

## with Accuracy (91%) and f1 score (92%))

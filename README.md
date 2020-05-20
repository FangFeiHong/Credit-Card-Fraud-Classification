# Credit-Card-Fraud-Classification
My own project to classify credit card fraud based on credit card features that concealed (except : Amount).

The dataset used for this project can be found [here](https://drive.google.com/file/d/1CTAlmlREFRaEN3NoHHitewpqAtWS5cVQ/view).
I got this dataset from a blog called Data Flair Training. In this dataset there are 29 features and 28 of them are concealed.

What I did on this project are :
* Data exploration
* Scalling (using StandardScaler)
* Data splitting
* Modelling (using Logistic Regression, Random Forest Classification, Artificial Neural Network, and XGBoost)
* Feature Importance

Result :
* For this dataset the best methods are XGBoost and Random Forest Classification (based on F1 Score).
* After filtering the feature based on feature importance on Logistic Regression model and fitted it to the model, the result weren't improved (again based on F1 Score).

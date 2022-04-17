# bank_transactions_gender_classifier
Analysis of bank transactions and modeling gender classifier

This is the Kaggle competition project (https://www.kaggle.com/competitions/python-and-analyze-data-final-project/overview).<br/><br/>
The main question is:<br/> 
Is it possible to predict the gender of a client using information on bank card receipts and expenditures?<br/> And if so, what is the accuracy of such prediction?<br/><br/>
The formal task:<br/> 
You need to predict the probability of gender "1" for each "customerid" that is present in the file gender_test_kaggle_sample_submission.csv.<br/><br/>
In the file "bank_transactions_gender_classifier.ipytb" I made EDA and dataset's preparing for the classification model.<br/>
In the file "model.ipytb" I made the classification model using XGBoost Classifier.<br/>
**The best ROC AUC score that I ever made is 0.86680.**

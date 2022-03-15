# Credit_Risk_Analysis
# Overview of the analysis:
----------------------------------------------
All over the world people borrow money to purchase homes and cars start a bussinesses and pursuu education .Loans are an essential part of modern society ,but loans present an opprtunity and challange for banks and other lending instituations on one hand loans create revenue with the intrest they generate ,on other hand there is a risk that borrowers won't be able to repay their loans and bank will lose money banks traditionally relied on measures like income ,credit score and collateral assets to assess lending risk ,so baiscally what we gonna do is use machine learning to analyze risk and process large amount of data that can help us make the final descion on approve the loan application.
i used python and scikit -learn to predict credit risk ,compare the strengths and weaknesses of machine learning model ,asses how the model gonna work.

# Results:
--------------------------------------------------

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.after  employ different techniques to train and evaluate models with unbalanced classes we got this results:

Technique | | Accuracy| Precision |Recall (Sensitivity)| F1 Score|
--- | --- | --- | --- |--- |--- |--- | --- |--- |--- |--- | --- |
Naive Random Oversampling | 301 | 283 | 290 | 286 | 
SMOTE Oversampling | 301 | 283 | 290 | 286 | 
UndersaCombination (Over and Under) Sampling 301 | 283 | 290 | 286 | 
Easy Ensemble AdaBoost Classifier | 301 | 283 | 290 | | 

# Credit_Risk_Analysis
# Overview of the analysis:
----------------------------------------------
All over the world people borrow money to purchase homes and cars start a bussinesses and pursuu education .Loans are an essential part of modern society ,but loans present an opprtunity and challange for banks and other lending instituations on one hand loans create revenue with the intrest they generate ,on other hand there is a risk that borrowers won't be able to repay their loans and bank will lose money banks traditionally relied on measures like income ,credit score and collateral assets to assess lending risk ,so baiscally what we gonna do is use machine learning to analyze risk and process large amount of data that can help us make the final descion on approve the loan application.
i used python and scikit -learn to predict credit risk ,compare the strengths and weaknesses of machine learning model ,asses how the model gonna work.

# Results:
--------------------------------------------------

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.after  employ different techniques to train and evaluate models with unbalanced classes we got this results for the high risk loans:

Technique | Accuracy| Precision |Recall (Sensitivity)| F1 Score|
--- | --- | --- | --- |--- |
Naive Random Oversampling | 65%| 0.01 | 0.71 | 0.02 | 
SMOTE Oversampling | 66% | 0.01 |0.69  |0.02  | 
Undersampling|  52% |0.01| 0.40| 0.01 | 
Combination| 68% | 0.01 | 0.80 | 0.02 | 
Balanced | 78% | 0.04 | 0.67 | 0.07 | 
Easy Ensemble|92%  |0.07  | 0.90 | 0.14 | 

and below is the codes for the unbalanced classes

![this is picture](https://github.com/Farah86/Credit_Risk_Analysis/blob/main/results/Naive.png)

![this is picture](https://github.com/Farah86/Credit_Risk_Analysis/blob/main/results/SMOTE.png)

![this is picture](https://github.com/Farah86/Credit_Risk_Analysis/blob/main/results/balanced.png)

![this is picture](https://github.com/Farah86/Credit_Risk_Analysis/blob/main/results/combination.png)

![this is picture](https://github.com/Farah86/Credit_Risk_Analysis/blob/main/results/easyensamble.png)

![this is picture](https://github.com/Farah86/Credit_Risk_Analysis/blob/main/results/undersampling.png)


-----------------------------------------------------------------------------------
# Summary:

so after doing the analyzing using the six machine learning models  we can defintly see the diffrence between the four (NAIVE, SMOTE,UNDERSAMPLING and COmbination) scores for the high risk loans and the two (BALANCED and EASY ENSEMBLE) with high accurancy scores espcially the Easy Ensemble AdaBoost Classifier with 92% showing that it is the most appropriate for assessing high-risk loans.



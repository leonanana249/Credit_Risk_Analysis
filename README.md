# Credit_Risk_Analysis

# Overview 

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results 
RandomOverSampler<br/>
![image](https://user-images.githubusercontent.com/107721712/198859821-0e7c4184-7e7d-40eb-adb9-ab9f4d856343.png)
![image](https://user-images.githubusercontent.com/107721712/198859829-7b7e56d7-26eb-4241-9258-201893cee7f6.png)<br/>
Accuracy Score <br/>
![image](https://user-images.githubusercontent.com/107721712/198860126-1eb9c695-a93d-4350-8260-c7e2576c77d1.png)


SMOTE<br/>
![image](https://user-images.githubusercontent.com/107721712/198859854-47bcad7f-8b29-4a0a-a380-c2d68e1fd527.png)
![image](https://user-images.githubusercontent.com/107721712/198859861-20c7476e-d82d-42db-8060-1730344e983b.png)<br/>
Accuracy Score<br/>
![image](https://user-images.githubusercontent.com/107721712/198860150-13f1461a-3000-4611-a6af-291cba0f6d61.png)

ClusterCentroids<br/>
![image](https://user-images.githubusercontent.com/107721712/198859926-b947e088-edfe-4819-ab9e-a33a44e7fa97.png)
![image](https://user-images.githubusercontent.com/107721712/198859929-8d61a549-47a7-4c93-b197-4ed0b870f309.png)<br/>
Accuracy Score <br/>
![image](https://user-images.githubusercontent.com/107721712/198860173-8fc4ea22-1193-4a5b-b7ba-0e1158349f78.png)

SMOTEENN<br/>
![image](https://user-images.githubusercontent.com/107721712/198859942-8564876e-9107-45cd-b24e-31e5e6a64184.png)
![image](https://user-images.githubusercontent.com/107721712/198859947-8adf5747-0959-428f-b515-0267f30a53e0.png)<br/>
Accuracy Score <br/>
![image](https://user-images.githubusercontent.com/107721712/198860199-cfe9d886-4172-4e58-bca0-2086d7623eba.png)

BalancedRandomForestClassifier<br/>
![image](https://user-images.githubusercontent.com/107721712/198859975-f340a120-e5db-438d-916b-adc159c98193.png)
![image](https://user-images.githubusercontent.com/107721712/198859981-cca395c4-e025-42fe-aa3f-1c89ed216338.png)<br/>
Accuracy Score <br/>
![image](https://user-images.githubusercontent.com/107721712/198860206-119d22bc-d00f-49ff-a01d-bd3c43252b0f.png)

EasyEnsembleClassifier<br/>
![image](https://user-images.githubusercontent.com/107721712/198860004-bd1b350f-ea38-4485-bcb0-f8467d56955b.png)
![image](https://user-images.githubusercontent.com/107721712/198860008-80a6c443-c4b0-4165-b2f3-2ee7ee9885c5.png)<br/>
Accuracy Score<br/> 
![image](https://user-images.githubusercontent.com/107721712/198860214-7d8005a6-5d65-420f-ad40-37609f3d10eb.png)

# Summary

For all models, EasyEnsembleClassifier is the most effectivev since it has the highest accuracy score for all Risk loans. The precision is low or none for all the models. In General, above the 90% of the current analysis, EasyEnsembleClassifier will perform a High-Risk loan precision as a great value for the overall analysis.

# Heart Disease Prediction

The aim of this project is to to predict heart disease (angiographic disease status) from a dataset of 14 features. 

Initially, EDA is performed on the dataset to figure out the important features in the given data. Then, 4 different machine learning algorithms (Logistic Regression, SVM, Random Forest, XGBoost) to predict Heart Disease are compared and the best model among them is chosen.

## Dataset Used 
UCI Heart Disease Data Set (https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

## Results
* The best results measured by AUC and Accuracy are obtained from a Logistic Regression model (AUC 0.96, Accuracy 0.88), followed by  a Gradient Boosting model. 
* From the set of 14 feaures, the most important ones to predict heart failure are whether or not there is a reversable defect in Thalassemia followed by whether or not there is an occurrence of asymptomatic chest pain.
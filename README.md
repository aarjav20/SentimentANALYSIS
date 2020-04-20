# SentimentAnalysis
This is sentiment analysis of twitter data. Dataset have been taken from https://www.analyticsvidhya.com/ twitter sentiment analysis hackathon problem.
In this Primarily three machine learning classification models have been used:-
1) Linear SVM
2) Random Forest Model
3) XgBoost Model

The metric used for evaluating the performance of classification models is F1-Score.

-> Precision = TP/TP+FP
-> Recall = TP/TP+FN
-> F1 Score = 2*(Recall * Precision) / (Recall + Precision)

Considering the F1 score of these models , the Random forest classification model performed best and beats the Linear svm model by narrow margin where as Xgboost model performed less compared to prior models.


 -> F1 score of respective models for final test data:-
1) Random Forest Model :- 0.705479452054794
2) Linear SVM :- 0.704273504273504
3) XgBoost Model :- 0.577861163227017

Future scope :-
1) Proper tuning of Xgboost model to improve results
2) Adding more efficient methods of cleaning the data for improved performance of models




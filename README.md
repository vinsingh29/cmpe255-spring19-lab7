# cmpe255-spring19-lab7

Results and Conclusion
I have used 4 classifiers:

1. Naive Bayes
It worked well in all the 3 scenario(when reviews: 1000,50000,300000). 
It classified postive (88%) and neutral (40%) classes very well. 
Classifier doesn't work that well for negative classes.

              precision    recall  f1-score   support

    Negative       0.48      0.17      0.25      4854
     Neutral       0.43      0.58      0.49     29942
    Positive       0.91      0.87      0.89    158490

2. Random Forest
This algorithm worked very well in all scenarios. 

              precision    recall  f1-score   support

    Negative       0.79      0.04      0.08      4854
     Neutral       0.57      0.13      0.21     29942
    Positive       0.84      0.98      0.90    158490

3. Knn 
This algorithm performed well when considering more than 50000 but less than 300000 reviews. 

4. SVM
This algorithm performed worst out of all above.

Conclusion:
Random forest did well in all scenarios compared to all above algorithms.

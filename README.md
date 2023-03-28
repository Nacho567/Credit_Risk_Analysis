# Credit Risk Analysis

## **Overview**

This was an analysis of credit loan risk using six different supervised machine learning models to see which one was the most efficient in predicting low and high risk loans. The six models were: Random Oversampling, Smote, Cluster Centroids, & SMOTEENN (resampling); Balanced Random Forest and Easy Ensemble Classifier (ensemble).

## **Results**

![Resampling Accuracy Scores](https://github.com/Nacho567/Credit_Risk_Analysis/blob/56f8be9592ff62a06f1e412a5afc6ded50efad76/Challenge_Code/Resources/resampling_acc_scores.PNG)
![Ensemble Accuracy Scores](https://github.com/Nacho567/Credit_Risk_Analysis/blob/f254a15f7da6fdea84cd191f39e2fd6e0d7c8307/Challenge_Code/Resources/ensemble_acc_scores.PNG)

In looking at the accuracy scores, the resampling models performed well enough, but the ensemble models performed at a higher rate.


**Random Oversampling**

![Random Oversampling classification report imbalanced](https://github.com/Nacho567/Credit_Risk_Analysis/blob/56f8be9592ff62a06f1e412a5afc6ded50efad76/Challenge_Code/Resources/random_over_classification.PNG)

**Smote**

![Smote classification report imbalanced](https://github.com/Nacho567/Credit_Risk_Analysis/blob/63d1d367b1bef78ff52733371c898d795ad81769/Challenge_Code/Resources/smote_classification.PNG)

**Cluster Centroids**

![Cluster Centroids classification report imbalanced](https://github.com/Nacho567/Credit_Risk_Analysis/blob/56f8be9592ff62a06f1e412a5afc6ded50efad76/Challenge_Code/Resources/clustroids_classification.PNG)

**SMOTEENN**

![SMOTEENN classification report imbalanced](https://github.com/Nacho567/Credit_Risk_Analysis/blob/56f8be9592ff62a06f1e412a5afc6ded50efad76/Challenge_Code/Resources/SMOTEENN_classification.PNG)

**Balanced Random Forest**

![Balanced Random Forest classification report imbalanced](https://github.com/Nacho567/Credit_Risk_Analysis/blob/7b78686e35052e50fee528d7e68d7bb34fae45bf/Challenge_Code/Resources/Balanced_classification.PNG)

**Easy Ensemble**

![Easy Ensemble Classifier classification report imbalanced](https://github.com/Nacho567/Credit_Risk_Analysis/blob/7b78686e35052e50fee528d7e68d7bb34fae45bf/Challenge_Code/Resources/EEC_classification.PNG)


## **Summary**

Overall, most models predicted low risk loans well enough, with all achieving essentially 100% precision. When it came to high risk loans on the other hand, there were few models that were precise but some that had a high sensitivity to make up for that. Balanced Random Forest and Easy Ensemble had the best high risk precision, with 3% and 9% respectively. Easy Ensemble also had a sensitivity of 92%, giving it a F1 score of 16%, the best of all models. I would recommend the Easy Ensemble model because of this. It might not be the most precise, but in this case it's better to have more false positives to account for the low amount of high risk loans. Better the applications be appealed or required to provide more information resulting in a low risk loan.

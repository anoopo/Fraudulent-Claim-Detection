#   Fraudulent-Claim-Detection

###   Objective

Global Insure wants to build a model to classify insurance claims as either fraudulent or legitimate based on historical claim details and customer profiles. By using features like claim amounts, customer profiles and claim types, the company aims to predict which claims are likely to be fraudulent before they are approved.

Based on this assignment, you have to answer the following questions:

* How can we analyze historical claim data to detect patterns that indicate fraudulent claims?
* Which features are most predictive of fraudulent behavior?
* Can we predict the likelihood of fraud for an incoming claim, based on past data?
* What insights can be drawn from the model that can help in improving the fraud detection process?

###   Implementation Steps

The solution to the problem is implemented through the following steps:

1.  Data Preparation
2.  Data Cleaning
3.  Train Validation Split 70-30
4.  EDA on Training Data
5.  EDA on Validation Data (optional)
6.  Feature Engineering
7.  Model Building
8.  Predicting and Model Evaluation

###   Evaluation and Conclusion

`Accuracy:` Random Forest has a higher accuracy (0.70) than Logistic Regression (0.58). This suggests that Random Forest correctly classifies a larger overall percentage of claims. However, accuracy can be misleading in imbalanced datasets.

`Sensitivity (Recall):` Logistic Regression has a much higher sensitivity (0.6622) compared to Random Forest (0.2027). This means Logistic Regression is better at identifying actual fraudulent claims. In fraud detection, high sensitivity is often crucial because missing fraudulent claims can be very costly.

`Specificity:` Random Forest has higher specificity (0.8628) than Logistic Regression (0.5619). This means Random Forest is better at correctly identifying legitimate claims

`Precision:` Both models have relatively low precision (around 0.33), indicating that when they predict a claim is fraudulent, they are only correct about 33% of the time. This leads to a high number of false positives.

`F1-Score:` Logistic Regression has a higher F1-score (0.4414) than Random Forest (0.25). The F1-score balances precision and recall, and in this case, Logistic Regression achieves a better balance.

The models developed represent a valuable step towards automating fraud detection for Global Insure. The Random Forest model, in particular, shows promise. However, the evaluation highlights the critical need to address the class imbalance in the data.

The models developed provide a foundation for automating fraud detection. The analysis highlights the importance of addressing data imbalance and carefully selecting evaluation metrics. Further improvements in feature engineering, model selection, and hyperparameter tuning can lead to a more robust and effective fraud detection system for Global Insure. This will ultimately help in reducing financial losses and streamlining the claims process.

###   Authors

* Akash Apoorv Yadav
* Anoop O
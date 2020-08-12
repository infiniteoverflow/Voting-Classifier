# Voting-Classifier

Voting Classifier is a machine learning model that trains on a collection of Classification models and predicts the output based on the prediction outputs of the individual classifiers that makes up the voting-classifier.

Here , We have considered IRIS Dataset and passed it through three classifiers :

- Logistic Regression
- Support Vector Machine
- Decision Trees

We have performed both **Hard Voting** as well as **Soft Voting** and achieved an accuracy of 1.0 on the dataset. This is because the IRIS Dataset is quite prone to Overfitting.

But in general **Soft Voting** performs better than **Hard Voting** , because Soft Voting takes into consideration the average of the probability vector of individual classes of each individual classifiers.
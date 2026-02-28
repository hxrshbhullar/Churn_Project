# Churn_Project

This is an attempt to implement Logistic Regression on a Netflix Churn data from Kaggle. This project covers feature engineering, EDA, model creation, model evaluation, and finally a business centric approach to turn the output of the model into a business driven insight.

The entire code can be classified into the steps below:
1. The code explores the descriptive analysis of the data and then summarizes it using visuals and group-bys.
2. Feature Engineering has been done to create RFM (Recency, Frequency, and Monetary) features from the original dataset.
3. Creation of a custom target column from the input variables. [NOTE: This resulted in an important discovery]
4. Creation of Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.
5. Evaluation of the above mentioned models.
6. Conversion to log-odds for a more business-centric probabilistic outputs.

Learnings from this project are mentioned below:
1. How target dependency with input variables can result in data leakage and unrealistic coefficient explosions.
2. First hand experience with correctly assessing Overfitting in a model.
3. Problem-solving and extensive self-study to ultimately diagnose the issues in this code.

**NOTE: This code is by no means a good approach to a better, practical model and furthermore it does not contribute to any business value. This code simply showcases my approach to a churn problem statement and figuring out the how's and what's on my own. This project shines a light on my inability to understand how models work, implementation of reusable code (OOPs principles) and an organised approach to handling the problem and writing the code.**

This project has been a good learning curve for me to get better at data analysis and machine learning.

# Sentimental-Analysis
Introduction: -
Initially the given data set is pre-processed to remove special characters, stop words and then all the text sentences were tokenised and the base words were extracted using stemming. This pre-processed data was vectorised to train the models. The popular ML models such as Logistic Regression, KNN, SVC, Decision Tree and Random Forest classifiers were used to train different models and compare the prediction results. Finally came up with a new algorithm using probabilities of Logistic regression and random forest classifier which improved the overall scores.

Steps Followed: -
•	Examining the dataset
•	Tokenising the sentences
•	Stemming
•	Vectorisation
•	Exploratory Data Analysis
•	Splitting the data set into training data and testing data
•	Handling class imbalance on the train set
•	Making the prediction of all data points as same class to establish base line score. 
•	Improving the score from base line using Logistic Regression, KNN, SVC, Decision Tree, Random Forest classifiers
•	Through observations I found out that geometric mean of probabilities of Logistic Regression and probabilities of Random Forest (fixing the threshold value as 0.7) gave an accuracy of almost 92% and ROC AUC score of 70%(approx). 
•	Above obtained scores were better compared to all other individual model scores.




Titanic Survival Prediction - Machine Learning Models
This project focuses on predicting passenger survival using the famous Titanic dataset from Kaggle. The objective is to apply multiple machine learning classification algorithms, analyze their performance, and compare their effectiveness.

🔍 Dataset
The Titanic dataset contains information about the passengers, such as:

Age

Sex

Ticket class

Fare

Number of siblings/spouses aboard

Survival status

This is a binary classification problem, where the target variable is:

Survived → 1 = Yes, 0 = No

✅ Models Applied
SVM (Support Vector Machine): Finds the optimal hyperplane to separate classes in high-dimensional space.

KNN (K-Nearest Neighbors): Predicts the class based on the majority vote from the nearest k neighbors.

Naive Bayes: A probabilistic classifier based on Bayes’ Theorem assuming feature independence.

Decision Tree: Uses a tree-like model of decisions and their possible consequences.

Gradient Boosting: Builds models sequentially where each model corrects the previous one’s errors.

AdaBoost (Adaptive Boosting): Boosting technique that updates weights of misclassified samples to improve accuracy.

LightGBM: A gradient boosting framework optimized for performance and speed.

📊 Evaluation
Each model’s performance was evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

These metrics helped assess classification effectiveness and error analysis.

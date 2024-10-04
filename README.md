Credit Card Fraud Detection Using Machine Learning
Credit card fraud is a critical issue for financial institutions and their customers, with the challenge being to detect fraudulent transactions in real-time while minimizing false positives. This project focuses on developing a machine learning model to accurately detect fraudulent transactions using a dataset obtained from Kaggle, containing transactions by European cardholders in September 2013.

Project Overview:
The dataset consists of 284,807 credit card transactions over two days, with 492 identified as fraudulent, resulting in a highly imbalanced class distribution (fraudulent transactions accounting for only 0.172%). All input features are numerical and have undergone Principal Component Analysis (PCA) transformation to ensure confidentiality.

Key steps in this project include:

Exploratory Data Analysis (EDA): Univariate and bivariate analyses were performed, along with outlier detection and removal.
Handling Class Imbalance: We applied under-sampling techniques to balance the dataset.
Dimensionality Reduction: Techniques were used for data visualization in lower dimensions.

Model Building: We implemented various classification models including:
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Classifier (SVC)
Decision Tree Classifier

Model Evaluation: Models were evaluated using cross-validation, ROC AUC scores, confusion matrices, and more to find the best fit. We found that SVC and Logistic Regression had the best performance, with SVC having a higher ROC AUC score.

Evaluation Metrics:
Cross-validation Score
ROC AUC Score
ROC Curve
Confusion Matrix
Classification Report
Average Precision Score
Area Under Precision-Recall Curve

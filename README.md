# Phishing-Website-Detection-
This project focuses on detecting phishing websites using a variety of machine learning algorithms. Phishing websites are fraudulent sites designed to steal sensitive information by masquerading as legitimate entities. The objective of this project is to build models that can accurately distinguish between phishing and legitimate websites.

Dataset: 

The dataset used in this project consists of labeled samples of both phishing and legitimate websites. Each sample contains various features that characterize the websites, including URL structure, website content, and other relevant attributes.

Machine Learning Algorithms

To build effective detection models, I experimented with a range of machine learning algorithms, including:

Decision Tree Classifier: A simple and interpretable model that creates a tree structure to classify samples based on their attributes.

Multilayer Perceptrons (MLPs): A type of deep learning neural network with multiple hidden layers, capable of learning complex patterns in the data.

Random Forest Classifier: An ensemble learning method that combines multiple decision trees to improve accuracy and robustness.

XGBoost Classifier: A powerful gradient boosting algorithm known for its high accuracy and efficiency in large datasets.

Autoencoder Neural Network: An unsupervised learning approach that can identify anomalies or unusual patterns in the data.

Support Vector Machine (SVM): A robust classifier that finds the optimal hyperplane to separate different classes.

Model Comparison and Results:

I compared the performance of each algorithm to identify the best approach for phishing website detection. The evaluation metrics included accuracy, precision, recall, and F1-score. Among all the algorithms, the XGBoost Classifier achieved the highest accuracy, making it the most effective model for this task.

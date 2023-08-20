# E-Mail Spam Classification Project:
This repository contains the code and resources for a machine learning project focused on email spam classification. The goal of this project was to develop and compare multiple methods for accurately classifying emails as either spam or legitimate. The project utilized a variety of machine learning techniques and natural language processing (NLP) methods to achieve the classification task.

## Methods Used:
1. **Manual Machine Learning Models:**
   We explored several traditional machine learning algorithms, including Support Vector Classifier (SVC), Random Forest, XGBoost, CatBoost, GradientBoosting, LGBMClassifier, and Logistic Regression. Each model was trained and evaluated on the dataset, and their performances were compared to identify the best-performing model.

2. **Naive Bayes Models:**
   We implemented both Multinomial Naive Bayes and Bernoulli Naive Bayes models, both with and without pipeline preprocessing. These probabilistic models are well-suited for text classification tasks like spam detection.

3. **Neural Network with Early Stopping:**
   A neural network architecture was designed for the classification task. We experimented with and without TensorFlow, utilizing the EarlyStopping technique to prevent overfitting. Neural networks are known for their ability to capture intricate patterns in textual data.

4. **Support Vector Machine with NLP Using GridSearch:**
   We applied Support Vector Machine (SVM) models with Bag of Words and Tf-Idf (Term Frequency-Inverse Document Frequency) representations. The models were optimized using GridSearch to fine-tune hyperparameters, taking advantage of NLP techniques to enhance feature representation.

## Conclusion:
In conclusion, this project provided a comprehensive exploration of various methods for email spam classification. It highlighted the strengths and weaknesses of different approaches and emphasized the importance of proper preprocessing and model selection. The code and findings in this repository serve as a valuable resource for anyone interested in tackling similar text classification challenges.

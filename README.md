# Statistical Analysis of Machine Learning Algorithms for Fraud Detection in Bank Transactions

As the use of online banking and e-commerce grows, detecting fraudulent transactions has become a critical issue for the financial industry. In this project, we evaluate the performance of five popular machine learning algorithms, namely logistic regression, random forest, gradient boosting, Recurrent Neural Network - LSTM, and Neural Network, in detecting fraud in a bank transaction dataset.

# How to run the program

- Make sure all the files are in the same directory
- Run the change_data.ipynb file first
- Next either run the Label Encoding.ipynb or One Hot Encoding.ipynb file

## Introduction

The rise of online banking and e-commerce has led to an increase in fraudulent activities in the financial industry. Detecting such frauds has become a challenging task due to the complex nature of financial data and the increasing sophistication of fraudulent activities.

This project aims to evaluate the performance of machine learning algorithms in detecting fraud in a bank transaction dataset. We investigate the impact of preprocessing technique, one-hot encoding with SMOTE, and perform feature importance analysis to identify the most significant features. Moreover, we perform statistical tests to determine the significance of performance differences between the models and provide additional support for our findings.

## Related Work

Several studies have been conducted on fraud detection using machine learning techniques. Many researchers have proposed various approaches to improve the performance of fraud detection models. For instance, [1] used an ensemble approach with a genetic algorithm to detect credit card fraud. [2] proposed a deep learning approach with autoencoders to identify fraudulent transactions in credit card data. [3] used a support vector machine algorithm to detect fraudulent transactions in credit card data.

## Dataset

We used a publicly available bank transaction dataset containing 284,807 records with 31 features, including the transaction amount, type, and time. Out of these records, only 492 were labeled as fraudulent transactions, making it an imbalanced dataset.

## Preprocessing

We performed various preprocessing techniques on the dataset, including one-hot encoding with SMOTE to balance the dataset. We also performed feature selection to identify the most important features in the dataset.

## Machine Learning Algorithms

We evaluated the performance of five popular machine learning algorithms, including logistic regression, random forest, gradient boosting, Recurrent Neural Network - LSTM, and Neural Network. We used the scikit-learn library to implement these models.

## Feature Importance Analysis

We performed feature importance analysis using the Random Forest algorithm to identify the most significant features in the dataset. The analysis helped us to understand the impact of each feature on the performance of the models.

## Evaluation Metrics

We used various evaluation metrics, including F1 score, recall, precision, ROC curve, and accuracy, to assess the models' performance comprehensively.

## Results and Analysis

Our study finds that the Recurrent Neural Network - LSTM and Gradient Boosting outperform the other models, with a perfect score on all evaluation metrics. Our study highlights the importance of preprocessing techniques and feature selection in developing effective machine learning models for fraud detection in bank transactions.

## Conclusion

In conclusion, this project demonstrates the effectiveness of machine learning algorithms in detecting fraud in bank transactions. Our study also highlights the importance of preprocessing techniques and feature selection in improving the performance of these models. Our findings provide insights into the use of machine learning techniques for fraud detection in the financial industry and suggest avenues for future research in this area.

## References:

[1] F. Sun, Y. Wang, and B. Li, "Credit Card Fraud Detection Based on Ensemble Learning with Genetic Algorithm," International Journal of Computational Intelligence and Applications, vol. 17, no. 2, pp. 1850016, 2018.

[2] L. Li, W. Shi, and Q. Yuan, "Credit Card Fraud Detection Based on Deep Learning and Autoencoder," Journal of Intelligent and Fuzzy Systems, vol. 37, no. 4, pp. 5171-5179, 2019.

[3] M. Manjari, P. S. Avadhani, and D. S. Suresh, "Credit Card Fraud Detection using SVM with Feature Selection," International Journal of Computer Applications, vol. 179, no. 36, pp. 12-18, 2018.

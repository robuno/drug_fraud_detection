**Abstract**

Anomaly detection in imbalanced datasets is vital for fraud detection in finance and healthcare. We replicate and extend prior work comparing one-class classifiers trained on either majority or minority data using Credit Card Fraud and Medicare Part D datasets. Evaluating One-Class SVM, GMM, and OCAN, we find that majority-class training consistently outperforms minority-class training—especially with One-Class GMM on credit card data (AUC ∼= 0.96). However, all models struggle with the Medicare dataset due to extreme imbalance and high dimensionality. Results highlight the importance of training regime, data representation, and calibration.

![ROC Curve](https://raw.githubusercontent.com/robuno/drug_fraud_detection/refs/heads/main/roc2.png)

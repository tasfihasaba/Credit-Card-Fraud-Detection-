# Credit Card Fraud Detection

## Introduction
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to build a robust model that can accurately classify transactions as fraudulent or legitimate.

## Dataset
The dataset used for this project is from the Kaggle Credit Card Fraud Detection dataset. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, with only 492 frauds out of 284,807 transactions.

## Project Structure
- **data**: Contains the dataset (`creditcard.csv`).
- **notebooks**: Jupyter notebooks with data exploration, preprocessing, model training, and evaluation.
- **models**: Serialized trained models.
- **src**: Source code for data preprocessing, model training, and evaluation.

## Results

The model achieved an accuracy of 97.3%. Below is the classification report and confusion matrix for the model:

### Classification Report:
              precision    recall  f1-score   support

           0       0.95      1.00      0.97       143
           1       1.00      0.95      0.97       153

    accuracy                           0.97       296
   macro avg       0.97      0.97      0.97       296
weighted avg       0.97      0.97      0.97       296

### Confusion Matrix:
            Predicted Fraud  Predicted Legitimate

## Future Work

- Implement other resampling techniques to handle class imbalance.
- Explore other machine learning algorithms.
- Fine-tune the hyperparameters of the existing model.
- Deploy the model as an API for real-time fraud detection.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss what you would like to change.

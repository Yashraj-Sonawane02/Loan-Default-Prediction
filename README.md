# Loan-Default-Prediction

# Loan Default Prediction

This project aims to predict whether a loan applicant is likely to default using a logistic regression model. Predicting loan defaults helps financial institutions reduce risk and make informed lending decisions.

The dataset contains numerical features such as age, income, loan amount, and loan term. The target variable is `default`, where:
- `1` indicates the person defaulted
- `0` indicates the person repaid the loan

To improve model performance on imbalanced data, **SMOTE (Synthetic Minority Over-sampling Technique)** is used. The project also includes visualizations to understand class separation and evaluate the model.

## Key Features
- Logistic Regression for binary classification
- SMOTE for handling class imbalance
- Feature scaling and preprocessing
- Model evaluation using accuracy, precision, recall


## 📈 Workflow

1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Scaled numerical features

2. **Class Imbalance Handling**
   - Applied `SMOTE` to oversample the minority class

3. **Modeling**
   - Used `LogisticRegression` from scikit-learn
   - Trained on oversampled data

4. **Evaluation**
   - Confusion Matrix
   - Accuracy, Precision



Bank Personal Loan Modelling (Loan Approval) Prediction Using Machine Learning

📌 Project Overview

This project focuses on predicting loan approval status using machine learning algorithms. By analyzing customer attributes such as credit score, income, age, marital       status, employment history, and debt-to-income ratio, the model determines whether a customer is likely to repay the loan. This system helps financial institutions          minimize risk, reduce processing time, and improve decision accuracy compared to traditional manual reviews.

🎯 Objective

To build a machine learning model that predicts whether a customer is eligible for a personal loan approval based on historical customer data and financial attributes.

🔍 Key Parameters

    * Credit Score

    * Income

    * Age

    * Marital Status

    * Gender

    * Employment History

    * Debt-to-Income Ratio

    * Other financial indicators

⚙️ Project Workflow
1. Data Collection & Preprocessing

       Collection of raw customer loan data.

       Handling missing values.

       Encoding categorical features.

       Feature scaling and normalization.

       Outlier detection and treatment.

2. Model Training

       Multiple machine learning models are trained on historical loan datasets to learn the relationship between customer parameters and loan approval decisions.

3. Model Evaluation

       The trained models are evaluated using:

       * Accuracy

       * Precision

       * Recall

       * F1-score

       * Confusion Matrix

The best-performing model is selected based on these metrics.

🤖 Machine Learning Models Used
               
    * Logistic Regression

    * Linear Regression

    * Decision Tree

    * Random Forest

    * Naive Bayes

    * Support Vector Machine (SVM)



🛠️ Technologies Used

Programming Language: Python

Libraries:

    * NumPy

    * Pandas

    * Matplotlib

    * Seaborn

    * Scikit-learn

    * IDE: Jupyter Notebook / VS Code

📂 Dataset Description

    * Customer demographic and financial details

    * Loan status (Approved / Denied)

    * Cleaned and preprocessed before training

| Model                        | Type                      | Description                                             | Accuracy (%)  |
| ---------------------------- | ------------------------- | ------------------------------------------------------- | ------------- |
| Logistic Regression          | Linear Classification     | Uses a logistic function to model binary outcomes       | 85% |
| Linear Regression            | Regression                | Predicts continuous values using a linear relationship  | 80% |
| Decision Tree                | Non-linear Classification | Splits data into branches based on feature conditions   | 88% |
| **Random Forest**            | Ensemble Learning         | Combines multiple decision trees to improve performance | **95%** ✅ |
| Naive Bayes                  | Probabilistic Model       | Based on Bayes' theorem with independence assumptions   | 82% |
| Support Vector Machine (SVM) | Margin-based Classifier   | Finds optimal hyperplane to separate classes            | 90% |

Conclusion

The Random Forest model achieved 95% accuracy, demonstrating strong predictive performance and effective handling of complex data patterns. Its ensemble approach improved generalization and reduced overfitting. While the results are promising, additional metrics like precision, recall, and F1-score should be considered for a more complete evaluation. Overall, the model proves to be a reliable and efficient choice for this task.

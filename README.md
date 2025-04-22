

# Titanic Survival Prediction: Classification Model Selection & Optimization

## 📊 Project Overview

This project focuses on building, comparing, and optimizing several classification models to predict passenger survival on the Titanic dataset. The primary goal was to establish a reliable, systematic workflow for model selection and hyperparameter optimization using cross-validation techniques.

## 📈 Objectives
- Compare the performance of various classification algorithms.
- Apply GridSearchCV for systematic hyperparameter tuning.
- Evaluate models based on both cross-validation (CV) score and final test accuracy.
- Demonstrate how to interpret model evaluation metrics for robust decision-making.

## 🛠️ Models Compared
- Logistic Regression (with LogisticRegressionCV)
- Linear Support Vector Classifier (LinearSVC)
- Ridge Classifier (with RidgeClassifierCV)
- Linear Discriminant Analysis (LDA)

## 🧪 Methods & Workflow
1. **Data Preprocessing:** Feature engineering and standardization.
2. **Pipeline Creation:** Combined preprocessing and classifiers using scikit-learn pipelines.
3. **Model Training & Tuning:** Applied GridSearchCV for hyperparameter optimization.
4. **Model Evaluation:** Compared models based on CV scores and test set accuracy.
5. **Convergence Issue Handling:** Managed convergence warnings with appropriate solver and iteration adjustments.

## 💡 Key Results
- Best Test Accuracy: **84.36%**
- Highest CV Score: **82.31%** with LogisticRegressionCV.
- All top-performing models maintained consistent test accuracy.

## 🔍 Insights
- Cross-validation score reflects model stability during training.
- Test accuracy represents real-world, unseen data performance.
- Importance of balancing both metrics to select reliable models.

## 📦 Applications
The workflow established here is highly transferable to:
- Medical diagnosis (binary disease classification)
- Fraud detection in financial transactions
- Customer churn prediction
- Text sentiment classification

## 📑 Tech Stack
Python, scikit-learn, Pandas, NumPy, Jupyter Notebook, Matplotlib

## 📎 Author
Mahdi Mohsseni | Data Scientist
[LinkedIn Profile](https://www.linkedin.com/in/mohsseni/)

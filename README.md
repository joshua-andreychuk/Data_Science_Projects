# Finance Fraud Prediction Using Machine Learning

## Project Overview

This project aims to predict fraudulent financial transactions using advanced machine learning techniques. By leveraging a comprehensive dataset, the project employs various data preprocessing, feature extraction, and model tuning strategies to achieve high accuracy and reliability.

## Key Features

- **Data Preprocessing**: Detailed steps to clean and prepare the data for modeling.
- **Feature Engineering**: Utilization of Principal Component Analysis (PCA) for dimensionality reduction while retaining essential information.
- **Model Training and Tuning**: Implementation of XGBoost with extensive hyperparameter tuning for optimal performance. The best model performance was achieved with a max depth of 8.
- **Performance Metrics**: Evaluation using metrics like Log Loss, ROC-AUC, and Accuracy to ensure model robustness. The model achieved over 99% training accuracy, over 98% test accuracy, and both training and test ROC AUC scores were over 99%.
- **Feature Importance Analysis**: Mapping PCA components back to original features to interpret model behavior.

## Technologies Used

- **Python**
- **Major Libraries**:
  - **Pandas**: For data manipulation and analysis.
  - **NumPy**: For numerical computing and array operations.
  - **Scikit-learn**: For machine learning algorithms and data preprocessing.
  - **XGBoost**: For the gradient boosting framework that was used as the primary model.
  - **Matplotlib and Seaborn**: For data visualization.

## Results

- **Best Model Performance**: The XGBoost model with a max depth of 8 demonstrated the most effective results.
- **Accuracy**: Achieved an impressive training accuracy of over 99% and a test accuracy of over 98%.
- **ROC AUC**: Both training and test ROC AUC scores were over 99%, indicating excellent model performance in distinguishing between classes.

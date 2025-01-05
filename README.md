# Titanic survival Prediction
# Project Overview
This project focuses on predicting passenger survival using logistic regression, based on a dataset containing various details about the passengers. The aim is to develop an accurate and reliable model that can predict which passengers survived the disaster.
# Problem Statement
Predicting passenger survival is crucial for analyzing historical data and improving safety measures. This project aims to develop a logistic regression model that accurately predicts which passengers survived based on various features.
# Data Cleaning
Data cleaning is essential to ensure the dataset's quality and reliability. The raw dataset may include missing values, inconsistencies, and outliers. The following steps were performed:
- **Handling Missing Values:** Missing values were imputed using appropriate strategies such as mean, median, or mode, or by removing records with excessive missing data.
- **Outlier Detection and Removal:** Outliers in continuous variables were identified and removed to prevent distortion in the model.
- **Standardization:** Standardized categorical variables and fixed formatting inconsistencies to ensure uniformity across the dataset.
  # Exploratory Data Analysis (EDA)
  EDA was conducted to understand the data better and to uncover patterns and relationships. The analysis included:
  - **Distribution Analysis:** Examined the distribution of key features such as age, fare, and class to understand their spread and central tendencies.
  - **Feature Relationships:** Explored the relationship between categorical features (e.g., sex, embarked) and survival using various visualizations.
  - **Insights:** Documented key findings such as the impact of class and age on survival to guide feature selection and model development.
  # Feature Engineering
  - **One-Hot Encoding:** Applied one-hot encoding to categorical variables like class, sex, and embarked to convert them into numerical format.
  - **Feature Scaling:** Scaled numerical features to ensure they contributed equally to the model.
  - **Feature Selection:** Based on EDA insights, irrelevant or redundant features were dropped to improve model performance.
    # Model Building
    The dataset was used to build and evaluate the logistic regression model for predicting passenger survival:
    - **Create Target and Feature Data:** The target variable is Survived and the feature variables are the rest of the dataset.
    - **Split Data:** The dataset is split into training and testing sets.
    - **Build Logistic Regression Model:** Train the logistic regression model using the training data.
      # Model Evaluation
      The model was evaluated using metrics such as accuracy, precision, recall, and F1-score. The logistic regression model achieved the highest accuracy, demonstrating its effectiveness in predicting passenger survival.
      # Results
      The results of the logistic regression model evaluation are as follows:
      - **Accuracy:** The model achieved a 75% accuracy, showing strong performance in predicting passenger survival.
      - **Precision:** The model's precision was 73% to ensure the correctness of positive predictions.
      - **Recall:** The recall score was 85% used to measure the model's ability to identify all positive instances.
      - **F1 Score:** The F1 score 79% to provided a balance between precision and recall.
      - **ROC Curve and AUC Score:** The ROC curve and AUC score were used to evaluate the model's overall performance.
        # Conclusion
        This project demonstrates the process of developing a predictive model for passenger survival using logistic regression. The logistic regression model was identified as the most effective for this particular dataset and problem, offering valuable insights and helping analyze historical data to improve safety measures.






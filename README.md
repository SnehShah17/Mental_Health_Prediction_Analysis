# Mental Health Prediction Analysis

## Overview

This project aims to analyze factors influencing mental health and build predictive models to determine whether an individual seeks treatment for a mental health condition. The dataset used contains various features such as age, gender, country, family history, and work-related factors.

## Dataset

The dataset includes the following columns:

- Timestamp
- Age
- Gender
- Country
- State
- Self-employed status
- Family history of mental illness
- Treatment sought
- Work interference
- Number of employees in the company
- Remote work status
- Tech company affiliation
- Mental health benefits provided by the employer
- Various other factors related to mental and physical health, workplace consequences, and personal opinions.

## Prediction Analysis

The target variable for prediction is "treatment," indicating whether an individual has sought treatment for a mental health condition. The following features are selected for prediction:

- Country
- Age
- Gender
- Family history
- Mental health benefits
- Work interference
- Mental health consequences
- Anonymity
- Wellness program availability
- Physical health consequences

![image](https://github.com/SnehShah17/Mental_Health_Prediction_Analysis/assets/75317219/2db036c7-809e-4a51-aeb7-5a5ed472a02b)

1. **Logistic Regression:**
   - Accuracy: 80.6%
   - Interpretation: Logistic regression is a simple model providing a baseline accuracy for mental health treatment prediction.

2. **Decision Tree Classifier:**
   - Accuracy: 85.5%
   - Interpretation: Decision tree classifier performs well, capturing non-linear relationships between features.

3. **Random Forest Classifier:**
   - Accuracy: 83.5%
   - Interpretation: Random forest, an ensemble of decision trees, maintains a high accuracy, offering robustness to overfitting.

4. **Gaussian Naive Bayes:**
   - Accuracy: 82.9%
   - Interpretation: Naive Bayes assumes independence between features, performing well despite its simplicity.

## Conclusion

The project explores the relationship between various factors and the likelihood of seeking mental health treatment. The decision tree classifier stands out with the highest accuracy, suggesting its effectiveness in capturing complex relationships within the data. Further fine-tuning and feature engineering could potentially improve model performance.

## Usage

To replicate the analysis, follow these steps:

1. **Dataset:**
   - Ensure you have the dataset with the required columns.
   - Preprocess the data as needed, handling missing values and encoding categorical variables.

2. **Code:**
   - Use the provided Python code for logistic regression, decision tree, random forest, and naive Bayes classification.
   - Adjust feature columns or model parameters based on your dataset characteristics.

3. **Run Analysis:**
   - Execute the code to train and evaluate the models.
   - Examine accuracy, confusion matrices, and other metrics to assess model performance.

4. **Further Exploration:**
   - Experiment with additional models, hyperparameter tuning, or feature engineering for enhanced predictive power.

Feel free to explore and contribute to the project for a deeper understanding of mental health factors and treatment-seeking behavior.

## Dependencies

- Python 3.x
- Required Python packages: pandas, numpy, scikit-learn, matplotlib, seaborn

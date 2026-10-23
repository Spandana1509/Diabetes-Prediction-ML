# Diabetes Prediction Using Machine Learning

## Project Overview
This project uses machine learning classification techniques to predict the likelihood of diabetes based on medical and health-related features in a dataset.

## Objectives
- Explore and understand the dataset.
- Perform data preprocessing and exploratory data analysis.
- Identify relationships between input features.
- Train a machine learning classification model.
- Evaluate model performance using classification metrics.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Load the diabetes dataset.
2. Inspect the data and check for missing values.
3. Perform data analysis and visualization.
4. Prepare the input features and target variable.
5. Split the data into training and testing sets.
6. Train the classification model.
7. Generate predictions on test data.
8. Evaluate the model using appropriate metrics.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## Model Results

Multiple machine learning classification models were trained and evaluated for diabetes prediction.

| Model | Training Accuracy | Test Accuracy |
|---|---:|---:|
| K-Nearest Neighbors (K = 9) | 95.83% | 95.25% |
| Decision Tree | 99.93% | 95.31% |
| Decision Tree (Max Depth = 3) | 97.18% | 97.22% |
| MLP Classifier | 96.59% | 96.47% |
| Scaled MLP Classifier | 97.22% | 97.24% |

### Key Findings
- The scaled MLP Classifier achieved the highest test accuracy among the models shown, at **97.24%**.
- The Decision Tree with a maximum depth of 3 achieved **97.22%** test accuracy.
- The unrestricted Decision Tree had much higher training accuracy than test accuracy, suggesting possible overfitting.

### Conclusion
The experiments demonstrate how different classification algorithms and feature scaling can affect predictive performance. The scaled MLP Classifier performed best among the displayed models based on test accuracy.

### Disclaimer
This project is for educational purposes only and is not intended for medical diagnosis.

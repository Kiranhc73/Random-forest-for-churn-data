# Telecom Customer Churn Prediction using Random Forest

This repository contains the code and results for a churn prediction model using the Random Forest algorithm on telecom customer data.

## Dataset

The dataset used for this analysis consists of telecom customer information, including features such as customer demographics, usage patterns, and service details. The target variable is the churn status, indicating whether a customer has churned or not.

## Model Performance

The Random Forest model achieved the following performance metrics on the test data:

- Accuracy: 80%
- Recall/Sensitivity: 71%

These metrics indicate that the model can correctly predict 80% of the churn cases, and among the actual churn cases, it can identify 71% of them.

## Repository Structure

- `data/`: Directory to store the dataset used for training and testing.
- `notebooks/`: Directory containing Jupyter notebooks with the code for data preprocessing, model training, and evaluation.
- `results/`: Directory to store the model performance results, such as classification reports and confusion matrices.
- `src/`: Directory containing the source code for the Random Forest model implementation.
- `README.md`: This documentation file.



## Conclusion

The Random Forest model achieved an accuracy of 80% and a recall of 71% on the telecom customer churn dataset. These results indicate that the model can effectively identify the majority of churn cases, making it useful for predicting potential churners. However, there is still room for improvement, and further analysis can be conducted to fine-tune the model or explore other algorithms.

If you have any questions or suggestions, please feel free to reach out. Happy coding!



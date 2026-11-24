# Naive Bayes – Social Network Ads Prediction

## Project Overview

This project applies the **Naive Bayes classification algorithm** to predict whether a user will purchase a product advertised on a social network based on two features: age and estimated salary.

The goal is to train a machine learning model capable of identifying potential customers using demographic and financial information.

## Dataset

The project uses the `Social_Network_Ads.csv` dataset, which contains the following features:

- **Age:** Customer's age.
- **Estimated Salary:** Customer's estimated annual salary.
- **Purchased:** Target variable indicating whether the customer purchased the advertised product (1 = Yes, 0 = No).

## Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Project Workflow

The project follows these steps:

1. **Data Loading:** Imported the dataset using Pandas.
2. **Data Preparation:** Separated the independent variables (Age and Estimated Salary) from the target variable (Purchased).
3. **Train-Test Split:** Divided the dataset into training (75%) and testing (25%) sets.
4. **Feature Scaling:** Applied StandardScaler to standardize the input features.
5. **Model Training:** Implemented and trained a Gaussian Naive Bayes classifier using Scikit-learn.
6. **Prediction:** Used the trained model to predict purchasing behavior on the test set.
7. **Model Evaluation:** Evaluated the model using a confusion matrix and accuracy score.
8. **Data Visualization:** Plotted the decision boundaries and classification results for both training and test sets.

## Model Performance

The Gaussian Naive Bayes classifier achieved an accuracy of **90%** on the test set.

### Confusion Matrix

| | Predicted: No | Predicted: Yes |
|---|---:|---:|
| Actual: No | 65 | 3 |
| Actual: Yes | 7 | 25 |

The model correctly classified 90 out of 100 observations.

## Visualizations

The project includes two visualizations:

- **Training Set:** Displays the decision boundaries learned by the model using the training data.
- **Test Set:** Shows how the classifier performs on unseen data, illustrating its predictions and decision boundaries.

## Key Takeaways

This project demonstrates the application of Gaussian Naive Bayes to a binary classification problem, covering data preprocessing, feature scaling, model training, evaluation, and visualization.

It also provides practical experience with Scikit-learn and fundamental machine learning concepts.

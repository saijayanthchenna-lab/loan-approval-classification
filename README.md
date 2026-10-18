&#x20;Loan Classification Using Logistic Regression



\## Project Overview

A Machine Learning classification project that predicts loan status using applicant-related information.



\## Objective

To build a binary classification model using Logistic Regression and evaluate its ability to distinguish between the two loan-status classes.



\## Dataset

\- File: `loan\_data.csv`

\- Records: Approximately 45,000

\- Features: Applicant demographics, income, employment experience, loan details, credit score and other attributes.

\- Target: `loan\_status`



\*\*Note:\*\* Confirm the meanings of target values 0 and 1 from the dataset documentation.



\## Technologies Used

\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- Jupyter Notebook



\## Machine Learning Workflow

1\. Data loading and inspection

2\. Exploratory Data Analysis (EDA)

3\. Data cleaning and outlier investigation

4\. Feature-target separation

5\. Train-test splitting

6\. Numerical feature scaling using StandardScaler

7\. Categorical feature encoding using OneHotEncoder

8\. Logistic Regression using a Scikit-learn Pipeline

9\. Hyperparameter tuning with GridSearchCV

10\. Model evaluation



\## Model Performance



\- Accuracy: 89.47%

\- ROC-AUC: 0.9523

\- Class 1 Precision: 0.77

\- Class 1 Recall: 0.75

\- Class 1 F1-score: 0.76



\## Hyperparameter Tuning

GridSearchCV with stratified 5-fold cross-validation was used to evaluate different values of C and class\_weight.



The selected configuration was:

\- C: 1

\- class\_weight: None



The best cross-validation ROC-AUC was approximately 0.9545.



\## How to Run

1\. Clone this repository.

2\. Install the required Python libraries.

3\. Open the notebook in Jupyter Notebook.

4\. Ensure the dataset is available at the expected path.

5\. Run the notebook cells in order.



\## Key Learning Outcomes

\- Binary classification

\- Data preprocessing pipelines

\- Feature scaling and categorical encoding

\- Confusion matrix and classification metrics

\- ROC-AUC

\- Cross-validation and hyperparameter tuning



\## Author

Sai Jayanth


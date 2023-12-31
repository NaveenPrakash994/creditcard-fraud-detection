git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection

# Credit Card Fraud Detection

This project aims to detect credit card fraud using machine learning techniques. It involves exploring, cleaning, and preprocessing credit card transaction data, building a predictive model, and evaluating its performance. The two main models utilized in this project are Logistic Regression and Random Forest Classifier.


## Getting Started

```bash

To use the Credit Card Fraud Detection project, follow these steps:

**Clone the Repository:**

   ```bash
   git clone https://github.com/NaveenPrakash994/creditcard-fraud-detection

```
Install the required dependencies using pip install -r requirements.txt
Download the dataset (creditcard.csv) and place it in the project directory

    
## Dependencies
Python 3.x
NumPy
Pandas
Seaborn
Matplotlib
Scikit-learn
SHAP
## Data Exploration and Cleaning
The initial steps involve exploring the dataset's structure, checking for duplicates, handling missing values, and understanding the distribution of legitimate and fraudulent transactions.
## Data preprocessing
Data preprocessing includes handling outliers using Isolation Forest, scaling 'Amount' using StandardScaler, and performing under-sampling to balance the classes.
## Model Selection
Two models, Logistic Regression and Random Forest Classifier, are trained and evaluated for credit card fraud detection. Hyperparameter tuning is performed using GridSearchCV.
## Model Evaluation
Model performance is assessed using accuracy, ROC-AUC scores, classification reports, and confusion matrices for both training and test datasets.
## Model Interpretability
Logistic Regression coefficients and SHAP (SHapley Additive exPlanations) values for Random Forest are explored for model interpretability.
## Saving Models
Saving Models
Trained models (Logistic Regression and Random Forest) are saved as pickle files (logistic_model.pkl and random_forest_model.pkl).

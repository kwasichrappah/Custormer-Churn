# Customer Churn Prediction Project

## Overview
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

This project aims to predict customer churn for a telecommunications company. 


## Problem Statement
The goal of this project is to develop a machine learning model that can accurately predict which customers are likely to churn. By identifying these customers early, the company can take proactive measures to retain them and minimize revenue loss.

## Dataset
The dataset used for this project contains historical information about customers, including features such as:
- Customer demographics (age and gender)
- Services subscribed (phone and internet)
- Contract details (contract length and payment method)
- Usage patterns (monthly charges, total charges, tenure)
- Churn status (whether the customer churned or not)

## Project Structure
- **data/**: Contains the dataset files.
- **notebooks/**: Jupyter notebooks for data exploration, preprocessing, and model development.`
- **models/**: Saved machine learning tuned and non-tuned models.
- **README.md**: Project overview and instructions.

## Getting Started
1. Clone the repository:

   git clone https://github.com/your_username/customer-churn-project.git
   cd customer-churn-project

2. Install dependencies:

   pip install -r requirements.txt

3. Explore the Jupyter notebooks in the `notebooks/` directory for data analysis and model development.
4. Run the scripts in the `src/` directory for model deployment or further analysis.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Model Evaluation
We evaluate the performance of the machine learning models using metrics such as accuracy, precision, recall, and ROC-AUC. Cross-validation and hyperparameter tuning techniques are used to optimize model performance.

## Deployment
The trained machine learning model can be deployed using the scripts provided. This allows real-time prediction of customer churn based on new data.

## Contributors
- Emmanuel Chrappah (emmanuel.chrappah@azubiafrica.org)
- Abigail Amponsah (abigail.amponsah@azubiafrica.org)
- Gabriel Kwatei (gabriel.kwatei@azubiafrica.org)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Data imbalance
Data imbalance affects machine learning models by tending only to predict the majority class and ignoting the minority class, hence, having major misclassification of the minority class in comparison with the majority class. Hence, we use techniques to balance class distribution in the data.

Models Training
Four different models were applied on the data and all results are reported with confusion matrix and classification report showing the precision, recall, and f1-score metrics.

Logistic regression Best parameters after several trials: C=200 (very large c value trying to fit the data as possible without overfitting), max_iter=1000
Support vector classifier Best prameters: kernel='linear', C=20
XGBoost classifier RandomizedSearchCV is used for hyperparameters tuning with StratifiedKFold of 5 splits.
Multi-layer Perceptron (MLP) classifier.
 

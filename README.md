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
- **notebook/**: Jupyter notebook for data exploration, preprocessing, and model development.`
- **models/**: Saved machine learning tuned and non-tuned models.
- **README.md**: Project overview and instructions.

## Getting Started
1. Clone the repository:

   git clone https://github.com/kwasichrappah/Custormer-Churn.git

   cd Customer-Churn
2. Install dependencies:

   pip install -r requirements.txt

3. Explore the Jupyter notebooks in the `notebook/` directory for data analysis and model development.
4. Run the scripts in the `src/` directory for model deployment or further analysis.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data analysis 
- Data cleaning
- Exploratory data analysis 
- Analytical questions 

## Models
- Logistic Regression
- SVC 
- XGBoost
- CatBoost

## Data balancing / Straification
Data imbalance affects machine learning models by tending only to predict the majority class and ignoring the minority class. The kind of method used is dependent on the datast and what the project tends to achieve. There are a number of methods to take care of that and they include :
- Undersampling
- Oversampling 
- SMOTE

## Model Evaluation
We evaluate the performance of the machine learning models using metrics such as accuracy, precision, recall, and ROC-AUC. Cross-validation and hyperparameter tuning techniques are used to optimize model performance.

## Deployment
The trained machine learning model can be deployed using the scripts provided. This allows real-time prediction of customer churn based on new data.


<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Emmanuel Chrappah**

-  Github:[Profile](https://github.com/kwasichrappah "Emmanuel Chrappah")
-  Email:[Email](mailto:emmanuel.chrappah@azubiafrica.org?subject=Hi "Hi!")
- Twitter: [Twitter Handle](https://twitter.com/jaychraps)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/emmanuel-chrappah-61115813b/)

🕵🏽‍♀️ **Abigail Amponsah**

-  Email:[Email](mailto:abigail.amponsah@azubiafrica.org?subject=Hi "Hi!")

🕵🏽‍♀️ **Gabriel Kwatei**

-  Email:[Email](mailto:gabriel.kwatei@azubiafrica.org?subject=Hi "Hi!")

##  Contributions 

Contributions, issues, and feature requests are welcome!


## ⭐️ Show your support
If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

## License
This project is licensed under the MIT License - see the LICENSE file for details.





# Credit-Card-Fraud-Detection
It is crucial for credit card companies to identify fraudulent transactions to ensure customers are not billed for unauthorized purchases.This dataset contains only numerical input variables that have been generated through a PCA transformation.
The features V1, V2, ... V28 are the principal components obtained through PCA. The only features that haven't been transformed with PCA are 'Time' and 'Amount'. The 'Time' feature represents the seconds elapsed between each transaction and the first transaction in the dataset.
The 'Amount' feature represents the transaction amount and can be utilized for example-dependent cost-sensitive learning. The 'Class' feature is the target variable, with a value of 1 indicating fraud and 0 indicating a legitimate transaction.
Accuracy from a confusion matrix is not a meaningful metric for unbalanced classification.

Download link for Kaggle https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

**Libraries**
* numpy
* pandas
* matplolib
* seaborn

**Algorithms**
* Logistic Regression
* Random Forest
* XGBoost

**Best Model || F1_Score = 86.22 || XGBoost**

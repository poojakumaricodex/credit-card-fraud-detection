# credit-card-fraud-detection
random forest &amp; cart algorithm
Credit Card Fraud Detection
This project aims to detect fraudulent transactions using machine learning algorithms, specifically Random Forest and CART (Classification and Regression Trees). By analyzing transaction patterns, the system classifies whether a transaction is fraudulent or legitimate, helping reduce financial losses and improve security.

Introduction
Fraudulent credit card transactions account for significant financial losses worldwide. This project provides an efficient solution using supervised machine learning techniques to classify fraudulent and legitimate transactions. The focus is on building models using Random Forest and CART algorithms to achieve high accuracy in detection.

Technologies Used
Programming Language: Python
Libraries:
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn

Dataset
The dataset used in this project is highly imbalanced, containing a large number of legitimate transactions and relatively few fraudulent ones. It includes features such as:

Time: Time elapsed since the first transaction.
V1, V2, ... V28: Principal components derived from PCA.
Amount: Transaction amount.
Class: Target variable (0 = Legitimate, 1 = Fraudulent).
You can download the dataset from Kaggle's Credit Card Fraud Detection dataset.


How to Run
Clone the repository:
git clone https://github.com/your-username/credit-card-fraud-detection.git  
cd credit-card-fraud-detection  

Install dependencies:

pip install -r requirements.txt  
Download and place the dataset in the project directory.

Open the project by clicking the Run button in your integrated development environment (IDE) or any Jupyter Notebook launcher.

Alternatively, you can run the script via command line:

python fraud_detection.py  
View results and visualizations.



Results
Random Forest achieved:

Accuracy: ~99%
AUC-ROC: 0.99
CART Algorithm achieved:

Accuracy: ~95%
AUC-ROC: 0.90

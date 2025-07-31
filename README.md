# Credit-Card-Fraud-Detection-GCAandDecisionTree
This project applies clustering and classification algorithms to detect fraudulent credit card transactions. The dataset used is highly imbalanced, with the majority of transactions being legitimate.

# Files in this Repository
CCFD.ipynb — Main Jupyter Notebook with preprocessing, clustering (KMeans), and classification (XGBoost) models.
creditcard.csv — Original dataset from Kaggle Credit Card Fraud Detection(drive-link is provided).

# Project Highlights
**Data Preprocessing** : Handling imbalance and normalization.
**KMeans Clustering** : Unsupervised detection of potential fraud clusters.
**XGBoost Classifier** : Supervised learning to improve detection accuracy.
**Evaluation Metrics** : Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

# How to Run
**1. Clone the repository**
   git clone https://github.com/sanjith-cmd/Credit-Card-Fraud-Detection-GCAandDecisionTree.git
   cd Credit-Card-Fraud-Detection-GCAandDecisionTree
   
**2. Install dependencies**
    pip install -r requirements.txt

**3. Open the notebook:**
    jupyter notebook CCFD.ipynb

**Dataset Info**
Transactions: 284,807
Fraudulent: 492 (0.172%)
Features: 30 (anonymized + Time, Amount)

**Source**
Dataset from: Kaggle - Credit Card Fraud Detection

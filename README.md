# Bank Transactions Anomaly Detection

A machine learning project that detects anomalous bank transactions using unsupervised learning techniques. The goal is to identify unusual transaction behavior that may indicate fraud, money laundering, or other suspicious financial activities without requiring labeled fraud data.

---

## 📌 Project Overview

This project applies anomaly detection algorithms to identify transactions that deviate from normal banking behavior. The workflow includes:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Dimensionality Reduction
- Anomaly Detection Modeling

---

## 📊 Dataset

The dataset contains historical bank transaction records with financial and customer transaction attributes.

Example features include:

- Transaction Amount
- Transaction Type
- Account Balance
- Customer Information
- Transaction Date and Time
- Merchant Information
- Transaction Location

> **Note:** No personally identifiable information (PII) is included in the dataset.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis

The exploratory analysis includes:

- Missing value analysis
- Distribution of transaction amounts
- Transaction frequency analysis
- Correlation analysis
- Outlier detection
- Feature distribution analysis
- Customer transaction behavior patterns

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Missing value handling
- Duplicate removal
- Categorical encoding
- Feature scaling
- Feature engineering
- Data normalization

---

## 📉 Dimensionality Reduction

To visualize high-dimensional transaction data and improve model interpretation, the project uses:

- t-Distributed Stochastic Neighbor Embedding (t-SNE)

---

## 🤖 Anomaly Detection Models

The following unsupervised machine learning models are implemented:

- Isolation Forest
- Local Outlier Factor (LOF)

These algorithms learn patterns of normal transactions and identify observations that significantly differ from expected behavior.

---

## 📊 Visualizations

The project includes visualizations such as:

- Transaction amount distributions
- Correlation heatmaps
- Boxplots
- Scatter plots
- t-SNE projections
- Detected anomaly visualizations

---
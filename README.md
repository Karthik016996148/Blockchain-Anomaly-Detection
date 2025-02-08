# 🔍 Blockchain Anomaly Detection Project

## 📌 Overview

This project detects **anomalous Bitcoin transactions** using **unsupervised machine learning** methods. We implement multiple anomaly detection techniques such as **Isolation Forest, CBLOF, PCA, K-Means clustering, and Autoencoders** to identify potential fraudulent activities in the blockchain network.

Our models analyze transaction patterns, including the **number of inputs, outputs, Bitcoin amount, and flagged suspicious transactions**. The results demonstrate promising performance in fraud detection, contributing to **enhanced security in cryptocurrency transactions**.

---

## 🚀 Technologies Used

- **Blockchain & Data Processing:**
  - 💰 Bitcoin Transaction Dataset (2011-2013)
  - ⛓️ Blockchain Network Analysis
- **Machine Learning & AI Models:**
  - 🌲 Isolation Forest
  - 📈 CBLOF (Cluster-Based Local Outlier Factor)
  - 🔍 PCA (Principal Component Analysis)
  - 🏷️ K-Means Clustering
  - 🤖 Autoencoder (Deep Learning)
- **Development & Tools:**
  - 🐍 Python (Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn)
  - 💾 Jupyter Notebook
  - 📊 Data Visualization (Matplotlib, Seaborn)

---

## 🔹 Project Workflow

### **1️⃣ Data Collection & Preprocessing**
- Dataset: **Bitcoin Transaction Network Metadata (2011-2013)**
- Features include transaction ID, wallet addresses, timestamps, and transaction values.
- Data cleaning, **feature selection, and normalization** applied.



---

### **2️⃣ Exploratory Data Analysis**
- **Heatmaps and Pair Plots** for understanding transaction distributions.
- **Clustering analysis** using K-Means and DBSCAN.
- **Feature Correlation Analysis** for identifying key transaction patterns.


---

### **3️⃣ Machine Learning Models**
We trained and evaluated multiple **unsupervised learning** models:

#### 🔍 **Isolation Forest**
- Detects anomalies by isolating fraudulent transactions.
- High accuracy but **challenges in reducing false positives**.

#### 🏷 **K-Means Clustering**
- Groups transactions into clusters to detect **abnormal patterns**.
- Moderate **recall rate** but **high false positives**.

#### 📈 **CBLOF**
- Categorizes transactions into **large clusters (normal)** and **small clusters (anomalous)**.
- High precision but **requires hyperparameter tuning**.

#### 📊 **PCA (Principal Component Analysis)**
- Reduces dimensionality while preserving transaction patterns.
- Improved **fraud detection performance** but **prone to overfitting**.

#### 🤖 **Autoencoder (Deep Learning)**
- Uses **neural networks** to detect anomalies based on reconstruction loss.
- Achieves the **best ROC-AUC score (0.94)**.



---

### **4️⃣ Performance Evaluation**
- **Metrics used:** Precision, Recall, F1-score, ROC-AUC, Confusion Matrix.
- **Best Performing Model:** **Autoencoder** due to **high recall and balanced precision**.


---

## 📊 Key Insights

- **High anomaly detection accuracy** using Autoencoder and Isolation Forest.
- **Significant false positives** in K-Means and Isolation Forest.
- **

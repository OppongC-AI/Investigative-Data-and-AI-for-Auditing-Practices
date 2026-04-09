# Investigative-Data-and-AI-for-Auditing-Practices
Overview

This project presents an AI-powered audit analytics framework designed to enhance internal auditing processes using machine learning.

Traditional audit methods struggle with large, complex datasets and often rely on manual sampling. This system leverages unsupervised and supervised learning techniques to:

Detect anomalies (potential fraud or irregularities)
Identify hidden risk patterns
Predict audit findings
Improve audit efficiency and accuracy

The goal is simple: move auditing from reactive to proactive decision-making.

Based on a real audit dataset with categorical and temporal features

🧠 Key Features
🔍 Anomaly Detection
Implemented using Isolation Forest
Identifies ~10% of records as outliers (potential fraud signals)
📊 Risk Clustering
Used K-Means clustering
Discovered 3 distinct audit risk profiles
🤖 Predictive Modeling
Built classification models:
Decision Tree
Random Forest
Predicts audit findings such as:
Fraudulent Activity
Non-compliance
Control Weakness
📉 Dimensionality Reduction
Applied PCA (Principal Component Analysis)
Reduced feature space for better visualization and efficiency
🛠️ Tech Stack
Python
Pandas / NumPy
Scikit-learn
Matplotlib / Seaborn
📂 Dataset
Source: Structured audit dataset (audit_dataset.csv)
Key Features:
Audit Date (converted to time features)
Department
Audit Findings
Risk Level (encoded: Low=0, Medium=1, High=2)
⚙️ Machine Learning Pipeline
Data Cleaning & Preprocessing
Feature Engineering (date extraction, encoding)
Dimensionality Reduction (PCA)
Clustering (K-Means)
Anomaly Detection (Isolation Forest)
Classification (Decision Tree & Random Forest)
Model Evaluation (Precision, Recall, F1-score)
📊 Results
PCA successfully revealed clear separations in audit patterns
Clustering identified meaningful operational groupings
Isolation Forest flagged high-risk anomalies linked to fraud indicators
Baseline model accuracy: ~34%
After hyperparameter tuning: 100% accuracy achieved

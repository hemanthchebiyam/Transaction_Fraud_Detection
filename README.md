# Transaction Fraud Detection using Random Forest

A machine learning project focused on detecting fraudulent credit card transactions using Random Forest classification algorithm.

## 📋 Project Overview

This project implements a fraud detection system for credit card transactions using machine learning techniques. The model analyzes transaction patterns to identify potentially fraudulent activities, helping financial institutions protect their customers from unauthorized transactions.

## 🎯 Objectives

- Build a robust fraud detection model using Random Forest algorithm
- Handle class imbalance in fraud detection datasets
- Evaluate model performance using appropriate metrics for imbalanced datasets
- Provide insights into feature importance for fraud detection

## 📊 Dataset Information

**Source:** [Kaggle - Credit Card Transactions by ealtman2019](https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions/data)

### Dataset Characteristics:
- **Type:** Synthetic credit card transaction data
- **Source:** IBM multi-agent virtual world simulation
- **Format:** CSV file with schema described in first row
- **Size:** 20+ million transactions
- **Coverage:** Decades of purchase history
- **Consumers:** 2000 synthetic US-based consumers with global travel patterns
- **Cards:** Multiple cards per consumer
- **Obfuscation:** Minimal data obfuscation for research purposes
- **Class Distribution:** Highly imbalanced (typical for fraud detection)
  - Legitimate transactions: ~99.8%
  - Fraudulent transactions: ~0.2%

### Key Features:
The dataset contains comprehensive transaction attributes including:
- Transaction amount and currency
- Merchant information and categories
- Timestamp and location data (global transactions)
- Customer demographics and profiles
- Card information (multiple cards per customer)
- Geographic data (US residents traveling worldwide)
- Purchase patterns across decades
- Binary fraud label (0 = legitimate, 1 = fraud)

### Data Advantages:
- **Realistic Simulation:** IBM's multi-agent system creates realistic transaction patterns
- **Comprehensive Coverage:** Decades of data with global transaction patterns
- **Multiple Cards:** Complex customer relationships with multiple payment methods
- **Minimal Obfuscation:** Clear, interpretable features for analysis
- **Large Scale:** 20+ million transactions provide robust training data

### Data Challenges:
- **Class Imbalance:** Fraudulent transactions are rare compared to legitimate ones
- **Temporal Complexity:** Decades of data require careful time-series handling
- **Geographic Diversity:** Global transactions add complexity to pattern recognition
- **Customer Behavior:** Multiple cards per customer create complex behavioral patterns

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Development environment

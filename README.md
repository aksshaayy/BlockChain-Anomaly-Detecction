# Anomaly Detection in Blockchain Transactions

## Overview
This project is a comparative study of various machine learning models used to detect anomalies in blockchain transactions. It focuses on three algorithms: Isolation Forest, K-Means clustering, and Long Short-Term Memory (LSTM). The primary objective is to assess the performance of these models in identifying irregular or potentially fraudulent activities in blockchain data.

## Features
- **Isolation Forest:** Detects anomalies by isolating outliers in the transaction dataset.
- **K-Means Clustering:** Groups similar transactions together and highlights anomalies as those that do not fit well into any group.
- **LSTM (Long Short-Term Memory):** Uses sequence modeling to detect anomalies based on the transaction history over time.

## Datasets
The datasets used in this project are structured blockchain transaction records. These datasets were cleaned and preprocessed before applying the anomaly detection models.

## Algorithms
1. **Isolation Forest:** A model that isolates anomalies instead of profiling normal data. It efficiently handles large datasets and is well-suited for identifying anomalies in high-dimensional data such as blockchain transactions.
2. **K-Means Clustering:** This unsupervised algorithm partitions data into clusters. Transactions that do not fit well into any cluster are flagged as potential anomalies.
3. **LSTM:** A type of recurrent neural network (RNN) designed to handle sequential data. It is used here to model the sequence of transactions and detect irregular patterns over time.

## Installation
To run the project, clone the repository and install the required dependencies.
```bash
git clone <your-repository-link>
cd Anomaly-Detection-Blockchain
pip install -r requirements.txt

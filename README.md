This project implements a Logistic Regression based fraud detection system
and a simple Retrieval-Augmented Explanation module using Nearest Neighbors.

When a new transaction is predicted, the system retrieves the most similar
historical transactions and explains the output.

🚀 Features

Logistic Regression (balanced class handling)

StandardScaler for normalization

KNN retrieval for RAG-style explanation

Synthetic dataset fallback if CSV not found

Fraud probability calculation

Human-readable risk explanation

🧠 Technologies Used

Python

Pandas, NumPy

Scikit-Learn (LogisticRegression, NearestNeighbors)

Classification Report / Model Evaluation

📁 File Included

credit_card_fraud_detection.py

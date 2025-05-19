# 🚨 Network Intrusion Anomaly Detection

This project focuses on detecting anomalous network activity, such as intrusions or cyber-attacks, using deep learning and machine learning models on the **KDDCup'99** dataset — a benchmark dataset containing labeled network traffic logs with normal and attack records.

---

## 📊 Dataset

The **KDDCup'99** dataset contains simulated network traffic with features extracted from connection logs. Each record is labeled as **normal** or an **attack** (DoS, Probe, R2L, U2R), making it suitable for both binary and multiclass classification tasks.

---

## 🧠 Models Implemented

- **Isolation Forest** (Unsupervised baseline)
- **LSTM Autoencoder**
- **Stacked LSTM Autoencoder**

---

## 📈 Evaluation Metrics

- Accuracy, Precision, Recall, F1-Score  
- ROC-AUC, PR-AUC  
- Confusion Matrix  
- Specificity, False Positive Rate (FPR), False Negative Rate (FNR)  
- Cohen’s Kappa, Matthews Correlation Coefficient (MCC)  
- Log-Loss  

---

## 🧪 Results Summary

The **Stacked LSTM Autoencoder** achieved the **highest accuracy (93%)** and demonstrated the best overall balance between precision and recall, significantly outperforming both the Isolation Forest and the standard LSTM Autoencoder models.

---

## 🛠️ Skills & Tools Used

- Python, NumPy, Pandas  
- Scikit-learn, Keras, TensorFlow  
- Deep Learning & Anomaly Detection  
- Data Preprocessing & Visualization  
- Model Evaluation & Reporting  

---




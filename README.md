# IoT Network Intrusion Detection Analytics using GA-CNN-LSTM-Attention

## Overview

This project develops a hybrid Deep Learning model for detecting network intrusions in IoT environments using the UNSW-NB15 dataset.

The solution combines:

- Genetic Algorithm (GA)
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)
- Multi-Head Attention

to improve intrusion detection performance while reducing data dimensionality.

---

## Dataset

**UNSW-NB15**

- 257,673 network traffic records
- 42 original features
- Multiple attack categories including DoS, Exploits, Reconnaissance, Fuzzers, Backdoor, and Normal Traffic

---

## Data Processing

- Data Cleaning
- Label Encoding
- Feature Scaling (StandardScaler)
- Stratified Train-Test Split
- Feature Selection using Genetic Algorithm

### Feature Reduction

42 Features → 22 Features

---

## Models Evaluated

- SVM
- KNN
- Random Forest
- ANN
- RNN
- LSTM
- GA-CNN-LSTM-Attention (Proposed)

---

## Results

| Metric | Score |
|----------|----------|
| Accuracy | 93.64% |
| Precision | 94.87% |
| Recall | 95.20% |
| F1-Score | 95.03% |

### Additional Metrics

| Metric | Value |
|----------|----------|
| False Alarm Rate | 9.15% |
| Missed Attack Rate | 4.90% |

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Google Colab

---

## Repository Structure

```text
├── GA_CNN_LSTM_Attention_UNSW_NB15.ipynb
├── README.md
```

---

## Key Skills

- Data Analytics
- Data Cleaning
- Feature Engineering
- Predictive Analytics
- Machine Learning
- Deep Learning
- Model Evaluation
- Data Visualization

---

## Author

**Tran Hoang Thanh Thu**

Data Analyst | Business Intelligence | Data Analytics

GitHub: https://github.com/ththanhthu2307-eng

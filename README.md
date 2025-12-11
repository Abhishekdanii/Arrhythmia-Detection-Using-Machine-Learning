# Arrhythmia-Detection-Using-Machine-Learning
This project aims to build an intelligent system that can automatically detect arrhythmias from ECG signals. Arrhythmias—irregular heartbeats—can be early indicators of cardiac issues, and timely detection plays a major role in preventive healthcare. Our project focuses on combining classical ML techniques with deep learning approaches to improve diagnostic accuracy and reliability.

⭐ Project Overview

We designed a complete machine learning pipeline that processes ECG signals, extracts meaningful heartbeat patterns, and classifies them into different arrhythmia types.
Because real‐world medical datasets often suffer from imbalance, we used SMOTE to generate synthetic samples for minority arrhythmia classes and improve training stability.

🔍 Machine Learning Models Explored

To understand which approach works best for ECG classification, we trained and compared multiple models:

Logistic Regression

Random Forest

LightGBM

XGBoost

These models were evaluated using Precision, Recall, F1-Score, Accuracy, and Cohen’s Kappa, ensuring a comprehensive assessment. Boosting models performed particularly well with complex ECG patterns.

🧠 Deep Learning Approaches

To explore advanced representation learning for ECG signals, we experimented with:

1️⃣ Convolutional Neural Networks (CNNs)

CNNs are effective at capturing local waveform patterns and temporal structures in ECG signals. Our initial experiments demonstrated promising performance and reduced manual feature engineering.

2️⃣ Capsule Networks (CapsNet)

We also initiated testing with CapsNet, a deep learning architecture designed to preserve spatial hierarchies between features—something very valuable in ECG morphology analysis.
CapsNet’s ability to understand the orientation and structure of waves (P-wave, QRS complex, T-wave) makes it a strong candidate for more robust arrhythmia classification, especially in cases where subtle shape variations matter.

🔧 Skills & Techniques Gained

This project strengthened our expertise in:

ECG preprocessing and noise filtering

Feature engineering for biomedical signals

Handling imbalanced medical datasets (SMOTE)

Model comparison and evaluation

Deep learning experimentation (CNN + CapsNet)

Building ML pipelines for healthcare applications

👥 Team

Developed by Team GenAI (4 members) and presented at TechnoPHILIA’25, the 8th National Level Poster & Project Competition at MIT Academy of Engineering, Alandi.

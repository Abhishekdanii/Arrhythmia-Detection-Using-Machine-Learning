# Arrhythmia-Detection-Using-Machine-Learning
This project builds an intelligent system for detecting arrhythmias from ECG signals using both classical machine learning techniques and emerging deep learning approaches. Arrhythmias—irregular heart rhythms—can indicate serious cardiac issues, and early detection is crucial for effective intervention. Our goal is to create a robust, accurate, and healthcare-focused classification pipeline.

⭐ Project Overview

We developed a full workflow that reads ECG signals, preprocesses them, extracts meaningful features, and classifies different heartbeat types.
To handle dataset imbalance—common in medical datasets—we applied SMOTE to oversample minority arrhythmia classes and improve model learning behavior.

🔍 Machine Learning Models

The project includes performance comparison across multiple ML models:

1] Logistic Regression

2] Random Forest

3] LightGBM

4] XGBoost

Metrics such as Precision, Recall, F1-Score, Accuracy, and Cohen’s Kappa were used to evaluate model performance comprehensively.

🧠 Deep Learning Using 8,000+ ECG Images

For deep learning, we used an ECG image dataset of more than 8,000 samples, where each heartbeat is converted into a 2D image representation. This allows neural networks to better learn waveform morphology and subtle heartbeat variations.

1️⃣ Convolutional Neural Networks (CNNs)

CNNs help automatically extract spatial and temporal ECG features from image-form heartbeats.

2️⃣ Capsule Networks (CapsNet)

CapsNet was explored for its ability to capture hierarchical relationships between ECG components like the P-wave, QRS complex, and T-wave, making it suitable for recognizing subtle arrhythmia patterns.

🔧 Skills & Techniques Gained

1] ECG preprocessing and denoising

2] Feature engineering

3] Imbalanced data handling with SMOTE

4] Model training, tuning, and evaluation

5] Image-based deep learning (CNN + CapsNet)

6] Building reproducible ML pipelines for healthcare

👥 Team

Developed by Team GenAI (4 members) and presented at TechnoPHILIA’25, the 8th National Level Poster & Project Competition at MIT Academy of Engineering, Alandi.

🚧 Deep Learning Module Status

The deep learning component (CNN & CapsNet) is currently in a working and experimental state, with ongoing improvements and evaluation.

Building ML pipelines for healthcare applications



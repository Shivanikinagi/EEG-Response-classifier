# EEG Response Classifier for Hemiplegia Patients

## 🧠 Project Overview

This project focuses on classifying EEG responses of hemiplegia patients as either **responding** or **non-responding** by comparing their brain activity patterns to those of healthy individuals. By applying advanced signal processing and machine learning techniques, the project aims to identify meaningful differences in brainwave patterns that can assist doctors in assessing patient recovery and optimizing rehabilitation strategies.

---

## 📌 Objectives

- Extract meaningful features from EEG data.
- Compare EEG patterns between healthy individuals and hemiplegia patients.
- Classify hemiplegia patient responses as **responding** or **non-responding**.
- Provide insights for clinicians to track patient recovery over time.

---

## 📊 Methodology

### 📥 Data Collection
- **EEG dataset of healthy individuals** for training.
- **EEG dataset of hemiplegia patients** for testing and evaluation.
- Multi-channel EEG recordings collected under controlled conditions.

### ⚙️ Pre-processing
- **Band-pass filtering** (0.5 Hz – 45 Hz) to retain relevant brainwave frequencies.
- **Artifact removal** (e.g., eye blinks, muscle noise) using Independent Component Analysis (ICA).
- Normalization and segmentation of EEG signals into meaningful epochs.

### 📈 Feature Extraction
- Time-domain and frequency-domain features:
  - **Mean, Standard Deviation, Skewness**
  - **Band Power** (Delta, Theta, Alpha, Beta)
  - **Entropy Measures**
- Signal transformation using **Fast Fourier Transform (FFT)** and **Wavelet Transform (DWT)**.

### 🤖 Model Development
- **Machine Learning Models:**  
  - Logistic Regression  
  - Random Forest  
  - Support Vector Machine (SVM)

- **Deep Learning Models:**  
  - 1D Convolutional Neural Network (CNN)  
  - Long Short-Term Memory (LSTM)  

### 📊 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix


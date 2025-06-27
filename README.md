# IntelliDent
Intellident is an intelligent dental imaging analysis system designed to assist dentists in diagnosing root canal issues through automated interpretation of dental X-rays using artificial intelligence. This project aims to improve diagnostic accuracy, reduce time, and provide dental practitioners with decision support for endodontic treatments.
# 🦷 AI Dental Radiograph Analysis
### 🧠 Automated Detection of Root Canal Treatment Using Machine Learning

---

## 📌 Project Overview

This project focuses on leveraging **Machine Learning (ML)** to automate the classification of dental radiograph images and identify whether a **Root Canal Treatment (RCT)** is present or not.

Radiographs are the primary diagnostic tool in endodontics, but manual interpretation can be error-prone, subjective, and time-consuming. This work proposes an ML-based approach to improve the accuracy and efficiency of RCT detection.

---

## 🦷 Background

- **Root Canal Treatment (RCT)** is used to treat infected tooth pulp.
- Dental X-rays (radiographs) are used to determine if RCT is needed or has been performed.
- Misinterpretation of radiographs can lead to incorrect diagnosis or treatment.
- There's a growing need for **AI-assisted dental diagnosis tools** to enhance clinical decision-making.

---

## 🎯 Objective

To build and evaluate machine learning models that can **automatically classify dental X-ray images** into:
- ✅ **RCT Present**
- ❌ **No RCT**

The goal is to reduce diagnostic subjectivity and provide dentists with reliable second opinions through AI.

---

## 🧾 Dataset

- **Source**: [Kaggle Dental Radiography Dataset](https://www.kaggle.com/datasets/imtkaggleteam/dental-radiography)
- **Content**:
  - 1500+ high-quality dental radiograph images
  - Balanced binary labels: `RCT` and `NoRCT`
- **Preprocessing**:
  - Grayscale conversion
  - Resizing to 64×64
  - Normalization
  - Flattening for model compatibility

---

## ⚙️ Methodology

### 🔹 1. Data Preparation
- Image loading using OpenCV
- Label assignment based on folder names
- Data splitting (Training 80%, Testing 20%)

### 🔹 2. Model Building
- Models evaluated:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors (KNN)

### 🔹 3. Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report
- ROC-AUC Score
- Visualizations: Training curves, prediction samples

---

## 📊 Results Summary

| Model                 | Accuracy | Notable Points                         |
|----------------------|----------|----------------------------------------|
| Logistic Regression  | ~94%     | Simple, interpretable baseline         |
| Random Forest        | ~96%     | Good generalization, high precision    |
| SVM (Linear Kernel)  | ~97%     | Best performer, robust to noise        |
| KNN                  | ~90%     | Sensitive to image scale and distance  |

> The SVM model achieved the highest accuracy and best overall performance.

---

## ✅ Key Takeaways

- ML models can effectively classify dental radiographs with minimal preprocessing.
- SVM and Random Forest were the most robust classifiers.
- High classification performance demonstrates potential for real-world clinical use.

---

## 🔬 Future Work

- Implement **Convolutional Neural Networks (CNNs)** for raw image learning
- Deploy a lightweight mobile/web app for real-time inference
- Expand to multi-class dental conditions: fillings, implants, cavities

---

## 📁 Project Structure

📦 AI_Dental_Analysis

┣ 📜 AI_Dental_Analysis.ipynb ← Core notebook with full analysis

┣ 📄 README.md ← This documentation




# IntelliDent
Intellident is an intelligent dental imaging analysis system designed to assist dentists in diagnosing root canal issues through automated interpretation of dental X-rays using artificial intelligence. This project aims to improve diagnostic accuracy, reduce time, and provide dental practitioners with decision support for endodontic treatments.
# 🦷 AI Dental Radiograph Analysis
### 🧠 Automated Detection of Root Canal Treatment from Dental X-rays Using Machine Learning

---

## 📝 Overview

This project applies **Machine Learning** techniques to classify dental radiograph images and determine whether a **Root Canal Treatment (RCT)** is present or not.

The objective is to create an automated tool that can assist dentists by analyzing X-ray images and predicting the presence of root canals — reducing diagnostic time and increasing accuracy.

---

## 🦷 What is Root Canal Treatment?

Root Canal Treatment is a procedure to remove infection from inside a tooth. Dentists typically use **radiographs (X-ray images)** to:

- Detect decayed or infected pulp
- Assess the extent of infection
- Plan or confirm treatment

Manual interpretation of these radiographs can be **error-prone** due to subtle image differences, lighting conditions, or clinician fatigue.

---

## ❗ Problem This Project Solves

- Radiographic analysis requires expertise and can vary among practitioners.
- Misinterpretation can lead to unnecessary or missed treatments.
- Automating this classification helps improve **reliability, speed**, and **objectivity** in dental diagnostics.

---

## 🤖 Why Use Machine Learning?

ML allows us to:
- **Learn from thousands of labeled X-ray images**
- **Extract hidden patterns** from image pixels
- **Classify new images accurately** with minimal delay

---

## 🎯 Project Objective

To develop and evaluate ML models that can accurately classify dental X-ray images into:
- **RCT Present**
- **No RCT**

Using image-based feature extraction and supervised learning techniques, this project builds models that predict the presence of root canals with high confidence.

---

## 📦 Dataset

- **Source**: Curated set of labeled dental radiographs
- **Preprocessing**:
  - Image resizing to uniform dimensions
  - Grayscale conversion
  - Normalization and flattening to feature vectors
- **Labels**: 
  - `RCT` – Root Canal Present
  - `NoRCT` – No Root Canal

---

## ⚙️ Project Workflow

1. **Image Loading & Visualization**
   - Sample display of dental X-rays with labels

2. **Preprocessing**
   - Resizing, grayscale normalization, pixel flattening

3. **Model Training**
   - Models used:
     - Logistic Regression
     - Random Forest Classifier
     - Support Vector Machine (SVM)
     - K-Nearest Neighbors (KNN)
   - Train-test split with performance comparison

4. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC Curve

---

## 🧪 Results

| Model                 | Accuracy | Comments                      |
|----------------------|----------|-------------------------------|
| Logistic Regression  | 94%+     | Fast and interpretable        |
| Random Forest        | 96%+     | Strong generalization         |
| SVM                  | 97%+     | Best performance (linear kernel) |
| KNN                  | ~90%     | Sensitive to data scaling     |

ROC-AUC curves confirm that **SVM** and **Random Forest** models are highly effective for this task.

---

## 🔚 Conclusion

This project demonstrates that **AI-driven models can effectively classify dental X-rays** to identify root canal treatments. It shows potential as a decision-support tool for dental practitioners.

---

## 🚀 Future Enhancements

- Use **Convolutional Neural Networks (CNNs)** for end-to-end raw image classification
- Train with larger and more diverse datasets
- Integrate with real-time dental imaging systems
- Build a GUI for dentists to upload and analyze images easily

---

## 📁 Repository Structure

📦 AI_Dental_Analysis

┣ 📜 AI_Dental_Analysis (Project Folder)

┣ 📄 README.md ← Project documentation (this file)





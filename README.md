# 🩺 Breast Cancer Classification using SVM and Neural Networks

## 📌 Project Overview
This project aims to classify breast cancer tumors as **Malignant** or **Benign** using two different machine learning models:
- **Support Vector Machine (SVM)**
- **Neural Network Classifier**

The goal is to compare their performance and identify which model is more accurate for this dataset.

---

## 📂 Dataset
- **Source:** [Breast Cancer Wisconsin (Diagnostic)
- **Features:** 30 numerical features (mean, standard error, worst values for cell measurements).  
- **Target:**  
  - `M` → Malignant (cancerous)  
  - `B` → Benign (non-cancerous)  

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Label encoding for target variable
   - Feature scaling (StandardScaler)

2. **Model Training**
   - Train and evaluate **SVM** model
   - Train and evaluate **Neural Network** model

3. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

---

## 📊 Results
| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| SVM                 | 97.3%    | 96%       | 98%    | 97%      |
| Neural Network      | 98.1%    | 97%       | 99%    | 98%      |

*Note: Results may vary depending on random seed and hyperparameters.*

---

## 🛠️ Technologies Used
- Python 3.x
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras (for Neural Network)
- Matplotlib, Seaborn

---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/USERNAME/breast-cancer-classification.git

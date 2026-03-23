# detect-sleep-states-decision-tree
Kaggle project for detecting sleep states using a Decision Tree model

# 💤 Detect Sleep States using Decision Tree

## 📌 Project Overview
This project is based on the Kaggle competition:
**Child Mind Institute - Detect Sleep States**

The goal is to predict sleep onset and wake-up events using wrist-worn accelerometer data.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Engineer meaningful time-series features
- Train a Decision Tree model
- Evaluate model performance

---

## 📊 Dataset
Dataset available on Kaggle:
https://www.kaggle.com/competitions/child-mind-institute-detect-sleep-states

⚠️ Note: Dataset is not included due to licensing restrictions.

---

## ⚙️ Approach

### 1. Data Preprocessing
- Handling missing values
- Sorting time-series data
- Feature normalization

### 2. Feature Engineering
- Rolling statistics (mean, std)
- Lag features
- Time-based features

### 3. Model
- Decision Tree Classifier
- Hyperparameter tuning

### 4. Evaluation
- Accuracy / F1 Score
- Confusion Matrix

---

## 📈 Results
- Model: Decision Tree
- Performance: (Add your score here)

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/detect-sleep-states-decision-tree.git
cd detect-sleep-states-decision-tree

pip install -r requirements.txt
python src/train.py

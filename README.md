# 🚢 Titanic Survival Prediction Using Machine Learning

## 📌 Overview
This project predicts whether a passenger survived the Titanic disaster using demographic and travel-related information. Multiple machine learning classification models are trained, cross-validated, and compared to select the best-performing model.

The project follows an end-to-end machine learning workflow including data preprocessing, model evaluation, visualization, and final prediction on unseen test data.

---

## 🎯 Objective
- Predict passenger survival (`Survived`)
- Perform exploratory data analysis (EDA)
- Train and compare multiple classification models
- Select the best model using **F1-score**
- Generate predictions for unseen test data

---

## 📊 Dataset
**Source:** Kaggle Titanic Dataset  

### Files Used:
- `train.csv` – Training & validation data
- `test.csv` – Unseen data for final prediction

### Key Features:
- `Pclass` – Passenger class  
- `Sex` – Gender  
- `Age` – Age of passenger  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Fare` – Ticket fare  
- `Embarked` – Port of embarkation  

### Target Variable:
- `Survived`  
  - `0` = Did not survive  
  - `1` = Survived  

---

## 🧠 Models Used
- Logistic Regression (Baseline)
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

---

## 🔬 Methodology
1. Data loading and inspection  
2. Missing value handling and data cleaning  
3. Encoding categorical variables  
4. Feature scaling  
5. Train–validation split  
6. 5-fold cross-validation  
7. Model comparison using F1-score  
8. Best model selection  
9. Prediction on test dataset  

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- **F1-score (primary metric)**  
- Confusion Matrix  

F1-score was prioritized due to class imbalance in the dataset.

---

## 📓 Notebook
Complete analysis and implementation is available in the notebook:


---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt

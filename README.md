# Hypertension-Prediction

A machine learning project for predicting hypertension based on patient health data. This notebook covers the full workflow from data exploration to model evaluation and hyperparameter tuning.

---

## 📊 Dataset Overview

The dataset contains **26,083 entries** and **14 features**:

| Column     | Description                       |
|------------|-----------------------------------|
| `age`      | Age of the patient                |
| `sex`      | Gender                            |
| `cp`       | Chest pain type                   |
| `trestbps` | Resting blood pressure            |
| `chol`     | Serum cholesterol                 |
| `fbs`      | Fasting blood sugar > 120 mg/dl   |
| `restecg`  | Resting electrocardiographic      |
| `thalach`  | Maximum heart rate achieved       |
| `exang`    | Exercise induced angina           |
| `oldpeak`  | ST depression from exercise       |
| `slope`    | Slope of ST segment               |
| `ca`       | Number of major vessels colored   |
| `thal`     | Thalassemia                       |
| `target`   | Hypertension diagnosis            |

Some missing values (e.g., in `sex`) were handled during preprocessing.

---

## 🛠️ Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Visualizations (distributions, correlations)

2. **Preprocessing**  
   - Handling missing values  
   - Feature scaling  
   - Train-test split

3. **Model Training & Evaluation**  
   - Models used:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Decision Tree
   - Metrics:
     - Accuracy
     - Precision
     - F1 Score
     - Confusion Matrix

4. **Hyperparameter Tuning**  
   - Applied Grid for optimal parameters

---

## 📈 Model Performance

| Model                | Accuracy | Precision | F1 Score | Confusion Matrix                         |
|---------------------|----------|-----------|----------|------------------------------------------|
| Logistic Regression | 0.8448   | 0.8224    | 0.8651   | `[[1809, 560], [249, 2594]]`             |
| KNN                 | 1.0000   | 1.0000    | 1.0000   | `[[2369, 0], [0, 2843]]`                 |
| SVM                 | 0.8484   | 0.8123    | 0.8711   | `[[1752, 617], [173, 2670]]`             |
| Decision Tree       | 0.9800   | 0.9800    | 0.9817   | `[[2312, 57], [47, 2796]]`               |

> ⚠️ The perfect performance of KNN might indicate overfitting and should be further validated.

---

## 💡 Conclusion
The Decision Tree model achieved strong performance with 98% accuracy, while KNN showed perfect scores, which might indicate overfitting.

---

## 📬 Contact
Author: Aymen Besbes & Aws Gandouz Email: Aymen.besbes@outlook.com | Aymen.besbes@ensi-uma.tn

LinkedIn: https://www.linkedin.com/in/aymen-besbes-158837245/

---

## 📅 Project Timeline
Original creation date: Dec 2023
Upload to GitHub: April 2025

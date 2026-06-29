# CodeAlpha\_DiseasePredictionModel

## 🚀 Project Title

**Disease Prediction using Machine Learning (Diabetes Dataset)**

---

## 📌 Objective

To develop a classification model that predicts whether an individual has diabetes based on various medical and physiological features. This project demonstrates the use of machine learning for health diagnostics and risk assessment.

---

## 📊 Dataset Information

- **Source:** [Pima Indians Diabetes Dataset](https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv)

- **Features:**

  - `Pregnancies`: Number of times pregnant
  - `Glucose`: Plasma glucose concentration
  - `BloodPressure`: Diastolic blood pressure (mm Hg)
  - `SkinThickness`: Triceps skin fold thickness (mm)
  - `Insulin`: 2-Hour serum insulin (mu U/ml)
  - `BMI`: Body mass index (weight in kg/(height in m)^2)
  - `DiabetesPedigreeFunction`: Diabetes likelihood based on family history
  - `Age`: Age in years
  - `Outcome`: (0 = Non-diabetic, 1 = Diabetic)

- **Note:** Some features contain 0s which are treated as missing values and replaced with the column mean.

---

## ⚙️ Tools & Libraries Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestClassifier, Logistic Regression, Evaluation Metrics)

---

## 🧪 ML Workflow

1. **Data Collection:** Loaded dataset from public GitHub source.
2. **Preprocessing:**
   - Replaced biologically invalid 0s with NaN.
   - Filled missing values with column means.
   - Standardized the features.
3. **Model Training:** Used Random Forest Classifier.
4. **Model Evaluation:**
   - Classification Report
   - Confusion Matrix
   - ROC-AUC Score
   - Feature Importance

---

## 📈 Model Performance

- **Accuracy:** 75%
- **Precision (Class 0):** 0.81
- **Recall (Class 1):** 0.65
- **ROC-AUC Score:** \~0.83

---

## 📷 Screenshots

All output visualizations are stored in the `screenshots/` folder:

- `confusion_matrix.png`
- `roc_curve.png`
- `feature_importance.png`

---

## 📁 File Structure

```
├── disease_model.ipynb            # Main notebook
├── disease_model.py               # Optional script version
├── data_info.txt                  # Dataset URL and description
├── README.md                      # Project documentation
├── screenshots/                   # Output plots
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
```

---

## 🏁 Conclusion

This project shows how machine learning models can be applied to medical data for disease prediction. The model performs reasonably well and can be further improved with hyperparameter tuning and ensemble techniques.

---

## 🙌 Acknowledgements

Thanks to **CodeAlpha** for providing this valuable learning opportunity and guidance through real-world ML projects.

---

## 🔗 Author

**Manikanta Pallepati**\
GitHub: [Manikanta545](https://github.com/Manikanta545)

> *This project is part of the CodeAlpha Machine Learning Internship.*


# 💳 Credit Card Fraud Detection with Random Forest

- Built a high-performing fraud detection model using Random Forest on a dataset of 568K anonymized transactions
- This project demonstrates end-to-end machine learning with model evaluation, cross-validation, and insightful visualizations.

---

## 🚀 Project Highlights

- **Model**: Random Forest (`F1 Score: 0.985` via 5-fold cross-validation)
- **Data**: 568,630 credit card transactions (balanced 50/50)
- **Target**: `Class` (1 = Fraud, 0 = Legitimate)
- **Features**: PCA-transformed (`V1`–`V28`) + `Amount`
- **Tech**: `scikit-learn`, `pandas`, `seaborn`, `matplotlib`

---

## 🧠 Key Features

- ✅ Trained random forest model with optimized depth/splits  
- ✅ Validated with cross-validation and test set evaluation  
- ✅ Visualized confusion matrix, feature importance, correlations, and ROC curve  
- ✅ Achieved **F1 Score of 0.985** via 5-fold cross-validation


---

## 📈 Model Performance

| Fold | F1 Score |
|------|----------|
| 1    | 0.9847   |
| 2    | 0.9864   |
| 3    | 0.9847   |
| 4    | 0.9843   |
| 5    | 0.9839   |
| **Avg** | **0.985** |

> The model achieved consistent performance across folds (≤ 0.3% variance)

---

## 📈 Visual Output

  ![image alt](https://github.com/masonbae/random_forest_cc_fraud/blob/0d410dbca64ec5f6356cac7cde6bc8d26e11bbbe/conufsion%20matrix.png)
- Feature Importance Bar Chart
- Correlation Heatmap
- ROC Curve with AUC

> Visuals available in the project notebook.

---

## 🛠 Tools Used

- **Language**: Python 3.11
- **Libraries**: pandas, numpy, scikit-learn, seaborn, matplotlib
- **Model**: RandomForestClassifier with cross-validation


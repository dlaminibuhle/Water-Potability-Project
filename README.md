# Water Potability Classification Project

This project aims to predict whether water is potable (safe to drink) based on various chemical properties. It was developed as part of a Statistics class assignment and includes a presentation, dataset, and a set of visualizations to support the analysis.

## 📁 Project Contents

- `Assignment 1.pptx`: Presentation summarizing the project
- `water_potability.csv`: Dataset used for analysis
- Visualizations: Plots generated from data analysis and model evaluation

## 📊 Dataset

The dataset contains 3276 samples with 9 chemical features and a binary target variable `Potability`:
- `0`: Not Potable
- `1`: Potable

### Features:
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

## 🧹 Preprocessing

- Missing values in `ph`, `Sulfate`, and `Trihalomethanes` were imputed using the median.
- All features were standardized (mean = 0, variance = 1).

## 🤖 Models Used

- Logistic Regression
- k-Nearest Neighbors (k=5)
- Decision Tree
- Random Forest

## 📈 Performance Metrics

- Evaluation metrics: F1-score and AUC
- Optimal cut-off threshold: 0.46 (based on Youden's J statistic)
- Best model: Random Forest
  - Accuracy: 0.68
  - F1 Score: 0.57
  - AUC: 0.71

## 🔍 Top 5 Most Important Features (Random Forest)

1. Sulfate
2. pH
3. Hardness
4. Solids
5. Chloramines

## 📷 Visualizations

- Class distribution of potable vs non-potable water
- Correlation heatmap of features
- Feature importance from Random Forest
- Model performance comparison (F1 Score & AUC)
- Distribution plots for top 5 features

Each visualization is included in the repository and can be viewed individually.

---

Feel free to explore the code, data, and presentation to understand how machine learning can be applied to water quality prediction.

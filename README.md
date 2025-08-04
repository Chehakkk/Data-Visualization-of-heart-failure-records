# ❤️ Heart Failure Dataset Analysis

## 📘 Overview
This project analyzes heart failure clinical data using Python and scikit-learn. It includes exploratory data analysis, outlier removal, preprocessing, and classification to predict patient survival. Our final model — **AdaBoostClassifier** — achieved an impressive **91% accuracy**.

---

## 📊 Exploratory Data Analysis (EDA)

- `df.info()` and `df.describe()` to inspect structure and statistical summaries.
- `boxplot()` to detect and visualize outliers.
- Outlier removal for improved data quality.
- `histplot()` and `barplot()` to view feature distributions and target class frequencies.
- `heatmap()` to examine feature correlations.

---

## 🧹 Preprocessing

- Encoded categorical features.
- Scaled numerical values.
- Split dataset into training and testing sets.

---

## 🤖 Model Training & Evaluation

Two classifiers were implemented for comparison:

| Model                  | Description                                     | Accuracy |
|------------------------|-------------------------------------------------|----------|
| `DecisionTreeClassifier` | Baseline tree-based model                    | **83%**  |
| `AdaBoostClassifier`     | Ensemble model using boosting techniques     | **91%**  |

---

## 🧠 Insights

- Outlier removal improved model generalization.
- AdaBoost significantly outperformed the standalone Decision Tree model.
- Strong feature correlations suggested opportunities for dimensionality reduction or feature selection in future iterations.

---

## 🚀 Future Improvements

- Apply cross-validation for robust model evaluation.
- Implement SHAP or LIME for interpretability.
- Package as an API using FastAPI or Flask.
- Tune hyperparameters to optimize performance.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn
- Jupyter Notebook

---


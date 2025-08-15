# 🧨 African Banking Crisis Classification Using Machine Learning

A supervised classification project that predicts banking crises in African countries using historical economic and financial indicators. This project applies machine learning models to identify crisis patterns and improve financial risk assessment strategies.

💻 Developed using Jupyter Notebook

---

## 🎯 Objective

This project is designed to help learners and analysts:

- Classify whether a country-year record is experiencing a banking crisis or not.
- Understand the relationship between inflation, debt default, currency crisis, and systemic indicators.
- Practice classification modeling using real-world imbalanced datasets.
- Evaluate models using confusion matrices and classification metrics like precision, recall, and F1-score.

---

## 📦 What's Included

The notebook guides users through a complete ML classification pipeline:

- 📥 **Data Loading & Exploration**
  - Dataset: `African_crises_dataset.csv`
  - Records: 1,059 observations
  - Target variable: `banking_crisis` (encoded as 0 = No Crisis, 1 = Crisis)
  - Class imbalance exists (only ~9% crisis)

- 🧹 **Data Preparation**
  - Dropped non-numeric columns (`country`, `country_code`)
  - Label encoded the target variable
  - Split into training and test sets (80/20 split)

- 🤖 **Model Training & Validation**
  - Classifier: `RandomForestClassifier` (500 trees)
  - 5-fold Cross-validation
  - High accuracy and generalization

- 📊 **Evaluation Metrics**
  - Accuracy: **99.06%**
  - Precision/Recall: High performance on both classes
  - Confusion Matrix: Visualized using Seaborn heatmap

---

## 🛠 Tech Stack

- **Language:** Python 3.x  
- **Notebook Environment:** Jupyter  
- **Libraries:** pandas, numpy, scikit-learn, seaborn, matplotlib

---

## 💡 Learning Experience

This project provided valuable experience with imbalanced classification problems in a real socio-economic context. I learned to:

- Clean and encode data effectively
- Handle class imbalance thoughtfully during evaluation
- Build robust classification models using Random Forest
- Visualize confusion matrices and interpret classification reports

---

## 🤝 Contributions

Pull requests and suggestions are welcome!  
Feel free to propose improvements, add new models, or extend the dataset analysis.

---

## 🙌 Acknowledgments

Thanks to open-source contributors and researchers who compile and release socio-economic datasets for public analysis.

---

## 🔗 Links

👉 [View Notebook on GitHub](https://github.com/Dee-elugs/African_Banking_Crisis_Classification/blob/main/Banking_Crisis_Model.ipynb)
"""

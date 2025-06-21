# 💧 Water Quality Prediction

This project aims to predict whether water is **potable (safe to drink)** using machine learning techniques. It uses the dataset `WaterPrurity.csv` and applies data preprocessing, visualization, model training, and evaluation to build a reliable water quality classifier.

---

## 📁 Repository Structure

```

📦WaterQualityPrediction/
├── README.md                       # Project documentation
├── WaterPrurity.csv                # Dataset used for training/testing
├── WaterQualityPrediction.ipynb    # Main Jupyter Notebook


````

---

## 🔍 Project Overview

The project addresses a real-world problem: determining the **drinkability of water** based on measurable properties. The notebook includes:

- **Loading and exploring the dataset**
- **Handling missing values**
- **Feature scaling**
- **Model training** using ML algorithms like:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- **Model evaluation** using classification metrics

---

## 📊 Dataset Details

**File**: `WaterPrurity.csv`

**Target Variable**: `Potability`  
(0 = Not Safe to Drink, 1 = Safe to Drink)

**Features**:  
`id`, `date`, `NH4`, `BSK5`, `Suspended`, `O2`, `NO3`, `NO2`, `SO4`, `PO4`, `CL`

The dataset includes missing values which are handled through imputation.

---

## ✅ Model Evaluation

* Accuracy and performance metrics are used to compare models
* Confusion Matrix, Precision, Recall, and F1-score help assess model reliability

---

## 🚀 Future Work

* Hyperparameter tuning with GridSearchCV
* Additional feature engineering
* Deployment as a web app using Flask or Streamlit



---

📚 License

This project is open-source under the MIT License.

---

## 🙏 Acknowledgements

* Dataset: Internal source (`WaterPrurity.csv`)
* Tools: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `jupyter`



---

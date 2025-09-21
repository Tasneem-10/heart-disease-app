# heart-disease-app
💓 Heart Disease Prediction App   An interactive Streamlit dashboard that uses machine learning models to predict the likelihood of heart disease based on patient data.   Includes ROC curves, feature importance visualization, model comparison, and manual/random patient testing.
# 💓 Heart Disease Prediction App

An interactive dashboard built with **Streamlit** that uses machine learning models to predict the likelihood of heart disease based on patient data.

---

## 🚀 Features

- ✅ Random Forest model for prediction
- 📈 ROC curve visualization
- 🧠 Feature importance chart
- 📊 Model comparison (Random Forest, Gradient Boosting, Logistic Regression)
- 📝 Manual and 🧪 random patient testing
- Clean interface with expandable sections

---

## 📊 Model Performance

The app compares three machine learning models trained on the heart disease dataset:

| Model                | Accuracy | ROC AUC | Precision (Class 1) | Recall (Class 1) | F1-Score (Class 1) |
|---------------------|----------|---------|----------------------|------------------|--------------------|
| **Random Forest**    | 98.5%    | 1.000   | 1.000                | 0.971            | 0.985              |
| Gradient Boosting    | 93.2%    | 0.981   | 0.916                | 0.951            | 0.933              |
| Logistic Regression  | 79.5%    | 0.879   | 0.756                | 0.874            | 0.811              |

> Based on these results, the **Random Forest** model is selected as the best-performing model.

---

## 🧠 How It Works

- The app uses a dataset of patient health metrics (age, cholesterol, blood pressure, etc.)
- Data is split into training and testing sets
- Models are trained and evaluated
- Users can test predictions manually or randomly
- Visualizations help interpret model behavior

---

## 📸 Screenshots

> Add screenshots of your app interface here, such as:
- Dashboard view
- ROC curve
- Feature importance
- Prediction result

Example:

```markdown
![Dashboard](Screenshot%202025-09-21%20142019.png)
![ROC Curve](Screenshot%202025-09-21%20142030.png)

pip install -r requirements.txt

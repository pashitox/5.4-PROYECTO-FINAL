
# 🏭 Employee Churn Prediction — Salifort Motors

**A machine learning and analytics project to anticipate employee departures and support strategic decision-making in talent management.**
![ROC Curve – Random Forest with AUC of 0.99](https://github.com/user-attachments/assets/27009016-4c4e-4b93-8c3d-b080e429d5ec)

## 📌 Project Objective

To develop a classification model capable of accurately predicting whether an employee is likely to leave the company, using variables such as satisfaction level, promotion history, workplace accidents, and performance scores.

## 🧠 Tools and Technologies

- Python 3.x  
- `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`  
- `Scikit-learn`, `XGBoost`  
- `Jupyter Notebook`  
- `Joblib` for exporting the model

## 📊 Dataset

- 14,000+ employee records  
- Key features:  
  - `satisfaction_level`  
  - `last_evaluation`  
  - `number_project`  
  - `average_monthly_hours`  
  - `time_spent_company`  
  - `Work_accident`  
  - `promotion_last_5years`  
  - `Department`  
  - `salary`  
- Target variable: `left` → 1 = left the company, 0 = stayed

## ⚙️ Models Trained

| Model                | Accuracy | Recall | ROC AUC |
|----------------------|----------|--------|---------|
| Random Forest        | 98.8%    | 96%    | 0.991   |
| XGBoost              | 98.7%    | 96%    | 0.991   |
| Logistic Regression  | 75.8%    | 23%    | Low     |

📌 *Random Forest achieved the best overall performance, with near-perfect metrics.*

## 📁 Repository Structure

```bash
📁 data/              # Processed dataset
📁 notebooks/         # EDA, visualizations, and model training
📁 modelos/           # .pkl files for trained models and encoders
📁 predicciones/      # Risk predictions per employee
📄 resumen_riesgo_por_departamento.xlsx
📄 README.md
```

## 📈 Key Visualizations

- Correlation heatmaps  
- Feature importance plots  
- Risk-level classification (High / Medium / Low)  
- Confusion matrix and ROC curve



## 💼 Model Applications

- Anticipating attrition in HR operations  
- Targeted retention strategies by department  
- Pre-screening new hires based on risk profile

## 🎯 Next Steps

- Integrate into internal HR dashboards  
- Add external variables like organizational climate and wellness surveys  
- Enhance model interpretability using SHAP

## 👤 Author

Project developed by **Juan M.** as part of a data science portfolio focused on workforce analytics and talent management.

## 📄 License

Distributed under the [MIT License](LICENSE)


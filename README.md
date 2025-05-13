# PROJECT-GREENLIGHT---Term-Life-Insurance-Conversion-Prediction
PROJECT GREENLIGHT - Term Life Insurance Conversion Prediction
# Project Greenlight: Term Life Insurance Conversion Prediction

## 🔍 Overview
**Project Greenlight** is a machine learning initiative designed to help HashSysTech identify which customers are most likely to convert on **term life insurance offers**. The model supports strategic telemarketing outreach by scoring leads based on demographic, behavioral, and campaign interaction data.

This project uses Random Forest and Logistic Regression classifiers to predict customer conversion (`yes`/`no`) and evaluates models using metrics like **ROC-AUC**, **precision**, and **recall**. The insights support smarter allocation of sales resources and improve campaign efficiency.

---

## 📁 Dataset
The dataset contains 45,211 customer records with features such as:

- `age`: Customer's age
- `job`, `marital`, `education_qual`: Demographic information
- `call_type`, `mon`, `day`, `dur`: Contact info
- `num_calls`, `prev_outcome`: Campaign performance history
- `y`: Target variable (conversion — yes/no)

---

## 🧠 Project Goals
- Build a predictive model for term life insurance conversion
- Evaluate model performance using AUC, confusion matrix, and F1-score
- Identify top features that influence customer conversion
- Visualize insights to support marketing and CRM targeting

---

## ⚙️ Technologies Used

| Category           | Tools                                      |
|--------------------|--------------------------------------------|
| Programming        | Python 3 (Google Colab)                    |
| Data Handling      | Pandas, NumPy                              |
| Machine Learning   | scikit-learn (RandomForest, LogisticRegression) |
| Evaluation Metrics | Confusion Matrix, ROC Curve, AUC, F1       |
| Visualization      | Matplotlib, Seaborn                        |

---

## 📊 Key Results
- **Random Forest AUC**: ~0.91
- **Top Features**: `dur`, `num_calls`, `job`, `prev_outcome`, `month`
- Precision for converters: ~64%, Recall: ~33%

---

## 🚀 How to Run

1. Open the Google Colab notebook: `Project_Greenlight_Conversion_Model.ipynb`
2. Upload your dataset named `dataset.csv` (formatted like the Bank Marketing dataset)
3. Run all cells to:
   - Preprocess data
   - Train models
   - Evaluate performance
   - Visualize top features and ROC curve

---

## 📈 Visual Outputs

- ROC Curve comparing Logistic Regression and Random Forest
- Bar chart of Top 10 important features
- Classification reports (Precision, Recall, F1)

---

## 📌 Future Improvements
- Integrate with CRM for real-time lead scoring
- Deploy as a web app using Flask or Streamlit
- Use SMOTE to handle class imbalance
- Add XGBoost for further accuracy gains

---

## 👤 Author
**Roman Dobczansky**  
Licensed Insurance Professional | Data Analyst  
GitHub: [roboy88](https://github.com/roboy88)  
LinkedIn: [roman-w-dobczansky](https://linkedin.com/in/roman-w-dobczansky)

---

## 📄 License
MIT License — feel free to use, modify, or deploy with attribution.

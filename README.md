# 📉 Customer Churn Predictor

A machine learning project to predict whether a telecom customer will churn based on their service usage, contract type, and payment history. Built using **Logistic Regression** and **Random Forest**, this project includes EDA, training, model evaluation, and deployment structure.

---

## 📁 Project Structure

```
customer-churn-predictor/
├── data/                      # Dataset (telco_churn.csv)
├── model/                     # (Optional) Saved model files
├── notebooks/
│   └── customer_churn_predictor.ipynb  # Full EDA + training
├── requirements.txt           # Project dependencies
├── app.py                     # Streamlit app (optional)
└── README.md                  # Project documentation
```

---

## 📊 Dataset

- **Name**: Telco Customer Churn
- **Records**: ~7,000+
- **Target Column**: `Churn` (Yes/No)
- **Source**: [Kaggle / IBM Sample](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🧠 Models Used

| Model               | Accuracy | Precision (Churn=Yes) | Recall (Churn=Yes) | F1-score (Churn=Yes) |
|--------------------|----------|------------------------|--------------------|----------------------|
| Random Forest       | 78.9%    | 63%                    | 52%                | 57%                  |
| Logistic Regression | *YourValue%* | *YourValue%*             | *YourValue%*           | *YourValue%*             |

> Replace *YourValue%* with actual scores from your Logistic Regression model.

---

## 📈 Feature Importance (Logistic Regression)

Top features contributing to churn prediction:
- Contract type
- MonthlyCharges
- OnlineSecurity
- TechSupport
- Tenure

These were visualized using a bar chart of model coefficients.

---

## 🛠️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Rukum-Maurya/customer-churn-predictor.git
cd customer-churn-predictor
```

### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook notebooks/customer_churn_predictor.ipynb
```

### 4. (Optional) Run Streamlit app

```bash
streamlit run app.py
```

---

## ✅ Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
streamlit  # optional for app
```

---

## 🙋‍♂️ Author

**Rukum Maurya**  
🔗 [GitHub Profile](https://github.com/Rukum-Maurya)

---

## 📃 License

This project is open-source and intended for learning and portfolio building.

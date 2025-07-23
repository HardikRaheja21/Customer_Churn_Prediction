
# 📊 Customer Churn Prediction – ML Project 🚀

This project predicts telecom customer churn using a Logistic Regression model. It helps telecom companies identify customers at risk of leaving, enabling proactive retention strategies through an intuitive Streamlit web app.

---

## 📌 Problem Statement

Customer churn — when users stop using a service — is a significant challenge for telecom providers. Predicting churn can help companies engage such users through targeted offers or customer service before they leave.

---

## 🎯 Objective

Build a machine learning model that predicts whether a customer is likely to churn based on **4 core features**:
- Gender
- Tenure (months with the company)
- Contract Type (e.g., month-to-month)
- Monthly Charges

---

## 🧠 Model Overview

- **Algorithm:** Logistic Regression  
- **Framework:** scikit-learn  
- **Preprocessing:** Label Encoding, Feature Scaling (for charges)  
- **Metrics:** Accuracy, Precision, Recall, F1-Score  

---

## 🛠️ Tools & Technologies

- **Language:** Python 🐍  
- **Libraries:** pandas, numpy, scikit-learn  
- **Frontend:** Streamlit  
- **Version Control & Deployment:** GitHub, Streamlit Cloud  

---

## 📈 Dataset Features Used

| Feature           | Description                                      |
|------------------|--------------------------------------------------|
| `gender`         | Male/Female                                      |
| `tenure`         | Number of months with the company                |
| `Contract`       | Type of contract (Month-to-month, One year, etc.)|
| `MonthlyCharges` | Monthly fee charged to the customer              |

---

## 🚀 Streamlit Web App

The app allows users to enter customer information and predicts churn probability with a clean, interactive UI.

### 🔧 Features:
- Dropdowns and sliders for input
- One-click prediction
- Color-coded output:
  - 🟢 **Customer is likely to stay**
  - 🟡 **Customer is likely to churn**

---

## 📂 File Structure

```
customer-churn-prediction/
│
├── app.py                   # Streamlit app for predictions
├── train_model.py           # Model training and export
├── logistic_model.pkl       # Trained logistic regression model
├── scaler.pkl               # Trained scaler for normalization
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
└── .gitignore               # Files to ignore in version control
```

---

## ⚙️ Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/customer-churn-prediction
cd customer-churn-prediction
```

### 2. Set Up a Virtual Environment
```bash
python -m venv venv
```
**Activate it:**
- On Windows:
  ```bash
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

### 3. Install Required Dependencies
```bash
pip install -r requirements.txt
```

### 4. Train the Model (Optional)
```bash
python train_model.py
```

### 5. Launch the Streamlit App
```bash
streamlit run app.py
```
Your default browser will open the app at `localhost:8501`.

---

## 🌐 Live Demo

✅ [Try the Live App on Streamlit](https://customerchurnprediction-qq9izza5h3et2ma4j2tg9n.streamlit.app/)

---

## 🧪 Troubleshooting

- `streamlit: command not found`  
  → Activate your virtual environment.

- `logistic_model.pkl` or `scaler.pkl` missing  
  → Ensure you've run `train_model.py`.

- Library errors  
  → Run `pip install -r requirements.txt` to reinstall missing packages.

---

## 📫 Contact

For any queries, feedback, or collaboration requests, feel free to reach out:

**Hardik Raheja**  
📧 [hardik.21raheja@gmail.com](mailto:hardik.21raheja@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/hardikraheja21)

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub and consider sharing it!

---

## 📌 Tags

`#MachineLearning` `#Streamlit` `#LogisticRegression` `#CustomerChurn` `#Python` `#DataScience`


# 🧮 Waiter Tips Prediction

Predict how much tip a customer will leave based on features like total bill, gender, day, and smoking habits using machine learning. This project showcases a simple yet effective regression model built using Python, pandas, and scikit-learn.

![tip](https://img.shields.io/badge/ML-Regression-blue) ![status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project aims to predict the **tip amount** a customer would give at a restaurant using various features such as:

* Total bill
* Sex
* Smoking status
* Day of the week
* Time (Lunch/Dinner)
* Party size

It demonstrates the end-to-end machine learning workflow including:

* Data preprocessing
* Exploratory data analysis
* Feature encoding
* Model training
* Evaluation
* Deployment (via Streamlit)

---

## 🔍 Dataset

The dataset used is the **'tips'** dataset — a popular sample dataset for regression problems.

| Column       | Description                   |
| ------------ | ----------------------------- |
| `total_bill` | Total bill in USD             |
| `tip`        | Tip given                     |
| `sex`        | Gender of the customer        |
| `smoker`     | Whether the customer smokes   |
| `day`        | Day of the week               |
| `time`       | Lunch or Dinner               |
| `size`       | Number of people in the party |

---

## 🛠️ Technologies Used

* Python3
* pandas
* xgboost
* seaborn & matplotlib
* scikit-learn
* plotly

---

## 📈 Machine Learning Model

* **Model Used:** Lasso Regression
* **Target Variable:** `tip`
* **Evaluation Metric:** R2 score

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/amolrathod7875/Waiter-Tip-Pediction.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```


## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---



# 🧾 Invoice Payment Prediction

This project uses a logistic regression model to predict whether an invoice will be paid on time or late, based on features like invoice amount, payment method, discount, city, and more.

## 📌 Objective
To help businesses identify invoices likely to be paid late, enabling them to take proactive steps like reminders or tighter payment terms.

---

## 🧠 Technologies Used
- Python 🐍
- Pandas 📊
- NumPy
- Scikit-learn 🤖
- Jupyter Notebook

---

## 🧾 Dataset Features

| Column | Description |
|--------|-------------|
| Invoice Amount | Total amount of the invoice |
| Days Late | Number of days payment was delayed |
| Discount (%) | Discount given on the invoice |
| City_* | One-hot encoded city columns |
| Product Category_* | One-hot encoded product category columns |
| Repeat Client_Yes | Indicates if the client is a repeat client |
| Payment Method_* | One-hot encoded payment method columns |

---

## 📈 Model Used
- Logistic Regression (Binary Classification)

---

## 🚀 Manual Prediction Example

You can manually predict using:

```python
model.predict(new_data)

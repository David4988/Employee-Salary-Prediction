
# 💼 Employee Salary Prediction App

This project predicts whether an employee earns **more than $50K or not**, using machine learning and deep learning techniques — deployed with Streamlit for live interaction.

---

## 📊 Project Features

✅ Cleaned and encoded real-world salary data  
✅ Multiple ML models: Logistic Regression, KNN, SVM  
✅ Deep Learning models using Keras (Basic MLP & Deep MLP)  
✅ Pipeline-based preprocessing using `MinMaxScaler`, `LabelEncoder`  
✅ Final model deployed with `Streamlit` for web prediction  
✅ Supports batch prediction via CSV upload  
✅ Built with ❤️ by David

---

## 🧠 Models Used

| Model               | Status     |
|--------------------|------------|
| Logistic Regression| ✅ Tested |
| K-Nearest Neighbors| ✅ Tested |
| Support Vector Machine | ✅ Final Model |
| Basic MLP (Keras)  | ✅ Tested |
| Deep MLP (Keras)   | ✅ Tested |

---

## 🛠️ Tech Stack

- Python 🐍  
- Scikit-learn  
- Pandas & NumPy  
- Streamlit  
- Joblib  
- Matplotlib / Seaborn *(optional)*

---

## 🚀 Run Locally

1. Clone the repo:

```bash
git clone https://github.com/david4988/employee-salary-prediction.git
cd employee-salary-prediction
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:

```bash
streamlit run app.py
```

---

## 🌐 Deployed App

🔗 [Click here to try the app](https://employee-salary-prediction-davidson4988.streamlit.app/)

---

## 📂 Predict in Bulk

Upload a `.csv` file with the following columns for batch prediction:

```
age, education, occupation, hours-per-week, experience
```

Example input:

```csv
age,education,occupation,hours-per-week,experience
35,Bachelors,Exec-managerial,45,10
29,Masters,Sales,40,5
```

---

## 📢 Acknowledgements

* Dataset: UCI Adult Income Dataset
* Built as part of internship deliverable
* Deployed with ❤️ using Streamlit Cloud

---

## ✨ Author

**David**
Aspiring Fullstack ML Engineer | [LinkedIn](https://linkedin.com/in/david4988)

---

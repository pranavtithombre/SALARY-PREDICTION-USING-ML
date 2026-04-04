# 📊 Salary Prediction using Linear Regression



## 📌 Description
This project builds a Machine Learning model to predict salary based on years of experience using Linear Regression. The dataset is analyzed, visualized, and used to train a predictive model.

---

## 📂 Dataset
The dataset is taken from:
https://raw.githubusercontent.com/ybifoundation/Dataset/main/Salary%20Data.csv

It contains:
- Experience Years
- Salary

---

## ⚙️ Libraries Used
- pandas
- numpy
- matplotlib
- sklearn

---

## 🔍 Data Analysis

### ✔️ Data Cleaning
- No missing values found (`df.isnull().sum() = 0`)
- No duplicate records found (`df.duplicated().sum() = 0`)

### ✔️ Statistical Analysis
- Mean:
  - Experience Years: 5.15
  - Salary: 74743.62
- Median:
  - Experience Years: 4.6
  - Salary: 64472.5
- Standard Deviation:
  - Salary varies significantly

---

## 📈 Data Visualization
- Scatter plot created between:
  - Experience Years (X-axis)
  - Salary (Y-axis)
- Shows a **positive linear relationship**

---

## 🤖 Model Building

### Train-Test Split
- Training data: 80%
- Testing data: 20%

### Model Used
- Linear Regression

---

## 📊 Model Performance
- R² Score: **0.96**
- Indicates very high accuracy

---

## 📈 Result
- Model shows strong linear relationship
- Accurate salary predictions based on experience

---

##🚀 Future Improvements
- Add more features (education, job role)
- Use advanced models
- Deploy using Flask or Streamlit

---

## 🧠 Conclusion
This project is a beginner-friendly example of Linear Regression and demonstrates how experience impacts salary.

Example:

# 🎯 Student Performance Prediction

## 📌 Project Overview
This project predicts **student performance scores** based on multiple factors such as study hours, attendance, extracurricular activities, and previous scores.  
We explore **Linear Regression** and **Polynomial Regression** models to compare performance and detect overfitting.

---

## 📂 Dataset
We use a dataset containing the following features:

- `Hours_Studied`
- `Attendance`
- `Access_to_Resources`
- `Extracurricular_Activities`
- `Sleep_Hours`
- `Previous_Scores`
- `Internet_Access`
- `Tutoring_Sessions`
- `Peer_Influence`
- `Physical_Activity`

The target variable is:
- `Performance Score`

---

## 🧠 Approach
1. **Load and preprocess data**
   - Select relevant features
   - Handle missing values if any
2. **Exploratory Data Analysis (EDA)**
   - Visualize relationships between features and target
3. **Modeling**
   - Linear Regression
4. **Evaluation**
   - Compare R²,  and MSE
5. **Overfitting Check**
   - Compare Train vs Test R²
6. **Prediction Export**
   - Save predictions to `prediction.csv`

---

## 📌 Dependencies

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
## 📈 Results

### **Linear Regression**
- **Test R²:** ~76.99%
- **Test RMSE:** ~1.80
- **MSE:** 3.25

---

## 📉 Overfitting Check
We compared **Train R²** vs **Test R²** for both models:  
- ✅ No significant overfitting detected (**difference < 5%**).

---

## 📊 Visualizations
- 📌 **Pairplot** to explore feature relationships  
- 📌 **Predicted vs Actual Score** plot for performance visualization  

---
## 📤 Saving Predictions

- Predictions are saved in a CSV file

---

## 👩‍💻 Author

**Mariam Badr**  
Faculty of Computers & Artificial Intelligence, Cairo University  
[GitHub](https://github.com/Mariam-Badr-MB) – [LinkedIn](https://www.linkedin.com/in/mariambadr13/)

# energy-efficiency-prediction-using-ridge
# 📌 Ridge Regression – Energy Efficiency Prediction  

## 📖 Overview  
This project demonstrates the use of **Ridge Regression** for predicting the **Heating Load** of buildings using the **Energy Efficiency Dataset** (UCI ML Repository).  
Ridge Regression is compared with Normal Linear Regression to highlight how regularization improves generalization by preventing overfitting.  

---

## 📊 Dataset  
- **Source**: [UCI Energy Efficiency Dataset](https://archive.ics.uci.edu/ml/datasets/energy+efficiency)  
- **Features (X1–X8):**  
  1. Relative Compactness  
  2. Surface Area  
  3. Wall Area  
  4. Roof Area  
  5. Overall Height  
  6. Orientation  
  7. Glazing Area  
  8. Glazing Area Distribution  

- **Targets:**  
  - `y1` → Heating Load (used in this project)  
  - `y2` → Cooling Load (can also be predicted)  

---

## ⚙️ Tech Stack  
- **Python** 🐍  
- **Libraries**:  
  - `pandas`, `numpy` → Data Handling  
  - `scikit-learn` → ML Models  
  - `matplotlib` → Visualization  

---

## 🚀 Project Workflow  
1. Load dataset (`ENB2012_data.xlsx`)  
2. Preprocess data (select features & target)  
3. Split dataset into **Train/Test**  
4. Train models:  
   - Linear Regression  
   - Ridge Regression (with α = 10)  
5. Evaluate using metrics:  
   - R² Score  
   - MSE, RMSE, MAE  
6. Visualize **Actual vs Predicted** results  

---

## 📈 Results  

| Model               | R² Score | MSE   | RMSE  | MAE  |  
|----------------------|----------|-------|-------|------|  
| Linear Regression    | 0.89     | 15.3  | 3.9   | 3.1  |  
| Ridge Regression     | 0.91     | 12.4  | 3.5   | 2.8  |  

✅ Ridge Regression performed slightly better than Linear Regression by reducing error.  

---

## 🖼️ Visualization  
Sample plot of **Actual vs Predicted Heating Load**:  


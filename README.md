# release_cycle_prediction_project
Machine Learning model to predict release cycle duration using historical release data.

# 🧠 Release Cycle Prediction using Machine Learning

## 📘 Objective
This project predicts **release cycle duration (in days)** based on key project indicators, including RFCs, test cases, test pass rate, sign-off time, and IVB scope.

## 📊 Key Features
- Predicts release duration using historical data
- Compares Linear Regression and Random Forest
- Provides feature importance and residual visualization
- Uses real-time date and time-based data fields

## 🧱 Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## ⚙️ How to Run
1. Clone the repo  
2. Open `release_cycle_prediction_model.ipynb` in Jupyter or Colab  
3. Run all cells  
4. The model will train and generate performance metrics and charts

## 📈 Results
- Random Forest performed best with R² ≈ 0.9
- Number of RFCs and Test Pass Rate were most influential


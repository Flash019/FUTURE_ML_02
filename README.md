# 📈 Stock Price Prediction using LSTM | Future Interns ML Internship - Task 2

## 🔍 Task Overview

In **Task 2**, I tackled the problem of **stock price prediction** using **Time Series Forecasting** techniques. The project focuses on understanding market behavior and predicting future stock values — specifically for Apple Inc. (AAPL).

## 💡 What I Did

- 📥 Imported and cleaned the stock data (`AAPL.csv`)
- 📊 Performed exploratory data analysis (EDA) to visualize trends
- 🧠 Built a predictive deep learning model using **LSTM (Long Short-Term Memory)** networks
- 🧪 Evaluated model performance using **RMSE** and trend matching
- 📈 Visualized actual vs predicted stock prices

## 🧠 Key Learnings

- Time Series Decomposition and Feature Scaling
- Understanding windowing and sequence shaping for LSTM inputs
- The power of LSTM in capturing long-term dependencies in sequential data
- Techniques to reduce overfitting and improve model generalization

## 🚀 Model Performance

✅ The LSTM model produced highly accurate short-term predictions  
📉 RMSE was kept low, and predicted values closely followed actual stock movements  
📊 Visual alignment between the trend lines confirmed good predictive quality

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas`, `numpy` – Data preprocessing  
  - `matplotlib`, `seaborn` – Data visualization  
  - `tensorflow.keras` – LSTM model building  
  - `scikit-learn` – Scaling and evaluation  

## 🧪 How to Run
 **Clone the repository**:
   ```bash
   git clone https://github.com/Flash019/FUTURE_ML_02.git
   cd FUTURE_ML_02
pip install -r requirements.txt
jupyter notebook FUTURE_ML_02.ipynb



# ⚡ Short Term Load Forecasting

## 📌 Overview
This project focuses on predicting short-term electricity load demand using advanced Machine Learning and Deep Learning models.

---

## ⚙️ Models Implemented
- XGBoost
- LSTM (Long Short-Term Memory)
- Transformer Model
- Hybrid Models (XGBoost + LSTM, XGBoost + Transformer)

---

## 📊 Dataset
- 5 years of hourly electricity load data
- Data preprocessing: scaling, sequence generation

---

## 🛠️ Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- TensorFlow / Keras
- XGBoost

---

## 📈 Results
- Compared performance of all models
- Hybrid models showed improved accuracy
- (Add graphs/screenshots here)

---

## 🚀 Future Work
- Hyperparameter tuning
- Real-time load forecasting
- Deployment using web applications

---

## 🔗 Colab Notebooks
## 🔗 Colab Notebooks

- XGBoost Model: [Open in Colab]https://colab.research.google.com/drive/1PSTLCKJClpHKTc_n2jghP4QaNW0tmlBO?usp=sharing
- LSTM Model: [Open in Colab]https://colab.research.google.com/drive/1RUmneLXrB0Ay7LYlRwXdEEJ43MOzQc5_?usp=sharing
- Transformer Model: [Open in Colab]https://colab.research.google.com/drive/1ZSRd2h_-bbW-IhSVA9qseiWAOtLis5Xg?usp=sharing
- XGBoost + LSTM Hybrid: [Open in Colab]https://colab.research.google.com/drive/1uk42u09SrHZmFqkSGNyhXzTKvdKkhtEt?usp=sharing
- XGBoost + Transformer Hybrid: [Open in Colab]https://colab.research.google.com/drive/1WZaPeXMBri2X00HerKGbGFlmCGLOS2Kr?usp=sharing

---
## 📊 Model Performance

| Model        | RMSE | MAE | 
|-------------|------|-----|
| XGBoost     |   17.984 MW   | 25.045    | 
| LSTM        |  0.020    |   0.016  |
| Transformer |  0.019    |   0.014  |
| Hybrid  (xgboost+lstm)   |   22.827   |  16.503   |
|Hybrid (xgboost+transformer) | 11.302 | 8.627 |


---

## 📈 Results

### XGBoost
<img width="1014" height="470" alt="xgboost_actual_vs_predicted" src="https://github.com/user-attachments/assets/0dfa2606-2ef9-4580-a6b5-d3a3942c8f79" /> <img width="831" height="505" alt="xgboost_loss_curve" src="https://github.com/user-attachments/assets/13014f19-07eb-4d4e-a49d-18d2eed55646" />



### LSTM
<img width="1018" height="547" alt="lstm_actual_vs_predicted_curve" src="https://github.com/user-attachments/assets/f12fb04a-497e-4128-9409-03b2db493237" /> <img width="863" height="470" alt="lstm_loss_curve" src="https://github.com/user-attachments/assets/b42623a8-d65a-4887-b032-588fabf1b6d9" />



### Transformer
<img width="1001" height="547" alt="transformer_actual_vs_predicted_curve" src="https://github.com/user-attachments/assets/4ba3f0ac-dad1-447f-8ed8-89a5e2a7bc07" />  <img width="881" height="470" alt="transformer_loss_curve" src="https://github.com/user-attachments/assets/ae274f9f-9154-4f6a-b46f-77e9cac24857" />



### Hybrid Model(xgboost+lstm hybrid model)
<img width="994" height="528" alt="xgboost_lstm_hybrid_actual_vs_prediction_curve" src="https://github.com/user-attachments/assets/e05e9928-de70-4a88-b0b2-509890b07c9a" />   <img width="708" height="470" alt="xgboost_lstm_hybrid_loss_curve" src="https://github.com/user-attachments/assets/6008f036-7889-4458-882d-983491feb875" />



### Hybrid Model(xgboost+Transformer hybrid model)
<img width="994" height="528" alt="xgboost_transformer_hybrid_actual_vs_prediction_curve" src="https://github.com/user-attachments/assets/c7071345-d464-4e5e-95f6-98a63a38fe10" />   <img width="726" height="470" alt="xgboost_transformer_hybrid_loss_curve" src="https://github.com/user-attachments/assets/fdaae0bc-2d65-49cb-a3fd-e461d29cc28a" />


---

## 📌 Conclusion

- Hybrid models achieved better accuracy than individual models  
- LSTM and Transformer captured temporal patterns effectively  
- XGBoost provided strong baseline performance  



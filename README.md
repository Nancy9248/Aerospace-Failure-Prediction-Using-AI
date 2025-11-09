# Aerospace Component Failure Prediction 🚀

This project uses **Machine Learning (Random Forest Classifier)** to predict whether an aerospace component is likely to fail based on sensor data (vibration, temperature, pressure, humidity).

## 🧠 Features
- Synthetic dataset with realistic aerospace parameters  
- Data analysis using Pandas, Matplotlib, and Seaborn  
- Random Forest model trained for binary classification (failure / no failure)  
- Model saved and reloaded for real-time prediction  

## 📁 Files
- `aerospace_failure_prediction.ipynb` — Main notebook with all steps  
- `failure_prediction_model.pkl` — Trained model (optional)

## ⚙️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

## 📊 Example Prediction
```python
# Example input: [vibration, temp_mean, pressure, humidity]
new_data = [0.8, 72, 2.1, 40]
# Model output -> ⚠️ Warning or ✅ Normal

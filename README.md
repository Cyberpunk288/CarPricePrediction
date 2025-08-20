# Car Price Prediction

This project is a simple **machine learning model** to predict car prices using Python, pandas, and scikit-learn.  
It demonstrates how to preprocess categorical data, train a Random Forest model, and evaluate it with metrics.

---

## 🚀 Open in Google Colab
You can run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Cyberpunk288/CarPricePrediction/blob/main/predictingcarprices.ipynb)

---

## 📂 Project Files
- `predictingcarprices.ipynb` → Main notebook with preprocessing, model training, and evaluation.  
- `README.md` → Project documentation.  

---

## 📊 Dataset
A small sample dataset is used (replace with a real dataset for better results):

| Make   | Model     | Year | Mileage | Price  |
|--------|----------|------|---------|--------|
| Toyota | Corolla  | 2015 | 50000   | 15000  |
| Honda  | Civic    | 2017 | 30000   | 17000  |
| Ford   | F-150    | 2018 | 40000   | 25000  |
| BMW    | 3 Series | 2016 | 60000   | 27000  |
| Audi   | A4       | 2015 | 45000   | 30000  |

---

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Convert categorical features (`make`, `model`) into numerical using **one-hot encoding**.  

2. **Model Training**  
   - Train a `RandomForestRegressor` on the dataset.  

3. **Model Evaluation**  
   - Metrics used:  
     - **Mean Squared Error (MSE)**  
     - **R² Score**  

---



# 🚗 Predicting CO₂ Emissions and Fuel Consumption with ML + DL

This project aims to predict vehicle CO₂ emissions and fuel consumption using a hybrid Deep Learning and Machine Learning approach. We combine a Feature Transformer model (DL) with XGBoost (ML) and fuse their outputs using a meta-classifier to improve accuracy.

---

## 📌 Project Objective

To develop an intelligent system that:
- Predicts fuel consumption (L/100 km) and CO₂ emissions (g/km)
- Analyzes the impact of features like engine size, fuel type, and cylinders
- Combines predictions from both DL and ML models for enhanced accuracy

---

## 📁 Dataset Description

The dataset contains the following key columns:

| Feature                        | Description                          |
|-------------------------------|--------------------------------------|
| Engine Size (L)               | Engine displacement in liters        |
| Cylinders                     | Number of engine cylinders           |
| Transmission                  | Gear type (Auto/Manual etc.)         |
| Fuel Type                     | Type of fuel used (Petrol, Diesel...)|
| Fuel Consumption (City/Hwy)   | L/100 km in different conditions     |
| CO₂ Emissions (g/km)          | Target feature                       |

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- XGBoost
- Scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn (EDA & visualization)

---

## 🧪 Methodology

### 🔹 Step 1: Preprocessing
- Handled missing values and categorical encoding
- Scaled features using `StandardScaler`

### 🔹 Step 2: Model 1 - Deep Learning (Feature Transformer)
- Built with TensorFlow
- Learns deep feature representations
- Predicts fuel consumption and CO₂ emissions

### 🔹 Step 3: Model 2 - Machine Learning (XGBoost)
- Trained using original + engineered features
- Powerful gradient boosting for regression/classification

### 🔹 Step 4: Meta Classifier
- Combined predictions from DL & ML
- XGBoost used again to refine final output

---

## 📊 Results

- DL and ML models both performed well individually
- Meta-classifier achieved better generalization
- Key features impacting emissions: engine size, fuel type, and cylinders

---



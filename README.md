# 🚀 Vayupragna — AI Powered Air Pollution & Health Risk Forecasting

## 🌍 Overview

**Vayupragna (Air Intelligence)** is an AI-driven air pollution forecasting system that predicts **air quality and associated health risks up to 72 hours in advance**.

Unlike traditional Air Quality Index (AQI) systems that only display pollution levels, this project introduces a **Health Risk-based Air Quality Index (HAQI)** which translates pollution data into **real-world health impact predictions** such as respiratory and cardiovascular risks.

The system combines **machine learning models, environmental data, and epidemiological insights** to bridge the gap between **environment monitoring and public health awareness**.

---

## 🧠 Key Features

- 🔹 Predicts **air pollution levels up to 72 hours in advance**
- 🔹 Converts AQI values into **health risk predictions**
- 🔹 Uses **hybrid machine learning models (Random Forest + LSTM)**
- 🔹 Incorporates **meteorological data** such as temperature, wind speed, and pressure
- 🔹 Feature engineering using **lag features and rolling averages**
- 🔹 Data preprocessing including **outlier detection and missing value handling**

---

## ⚙️ Tech Stack

### Programming
- Python

### Machine Learning
- Random Forest Regressor
- LSTM Neural Network

### Data Processing
- Pandas
- NumPy
- Scikit-learn

### Visualization
- Matplotlib
- Seaborn

### Data Sources
- Environmental pollution datasets
- Meteorological data
- Satellite air quality data

---

## 📊 Model Performance

| Model | R² Score |
|------|------|
| Random Forest | **0.936** |
| LSTM | **0.847** |

Random Forest achieved the best performance in predicting air pollution levels.

---

## 🏙 Case Study — Delhi Air Quality

The model was tested using **Delhi pollution data**.

### Key Results

- Predicted **"Very Unhealthy" pollution events 72 hours in advance**
- Identified **historical pollution levels and temperature** as major drivers
- Achieved **34% accuracy in predicting respiratory hospital admissions**

---

## 🧩 Project Architecture
Environmental Data
│
▼
Data Preprocessing
│
▼
Feature Engineering
│
▼
Machine Learning Models
(Random Forest + LSTM)
│
▼
Health Risk Prediction (HAQI)
│
▼
72 Hour Pollution Forecast


---

## 📈 Example Outputs

The system generates:

- Pollution forecast graphs
- Health risk trend analysis
- AQI prediction dashboards
- Environmental data insights

---

## 🎯 Real-World Impact

Air pollution causes **over 7 million deaths globally each year**.

Vayupragna aims to:

- Provide **early pollution warnings**
- Translate environmental data into **health insights**
- Support **public health awareness**
- Enable **data-driven environmental decision making**

---

## 🚀 Future Improvements

- Real-time **IoT sensor integration**
- Mobile app for **personalized health alerts**
- Hyper-local pollution prediction
- Deployment as a **public health API**

---

## 👨‍💻 Authors

- Aman Verma  
- Lavanya  
- Tarun  
- **Akshat Tyagi**

Guru Gobind Singh Indraprastha University

---

## ⭐ Support

If you found this project useful, consider **starring the repository** ⭐ to support the work.

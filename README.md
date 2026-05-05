# MiniProject_DS_AIML-A_2026_Energy-saver-household-enery-consumption-prediction
#  EnergySaver: Household Energy Consumption Prediction

##  Project Overview

EnergySaver is a data science project that predicts household energy consumption using smart meter data. The system analyzes historical energy usage patterns and provides future consumption estimates based on time and previous usage.

This project demonstrates an end-to-end machine learning pipeline, from data preprocessing to deployment using a Streamlit web application.

---

##  Problem Statement

With increasing energy demand, it is important to understand and predict household energy consumption. Manual analysis of energy usage is inefficient and does not provide actionable insights.

This project aims to:

* Predict energy consumption based on time and usage history
* Help users monitor and optimize electricity usage
* Support smarter energy management decisions

---

##  Objectives

* Analyze household energy data
* Build a machine learning model for prediction
* Perform feature engineering on time-series data
* Deploy the model using Streamlit

---

##  Project Structure

```
EnergySaver/
│
├── data/
│   └── energy_data.csv
│
├── notebooks/
│   └── energy_analysis.ipynb
│
├── models/
│   └── model.pkl
│
├── app/
│   └── app.py
│
├── requirements.txt
└── README.md
```

---

##  Technologies Used

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Model:** Random Forest Regressor
* **Deployment:** Streamlit
* **Environment:** Google Colab / VS Code

---

##  Workflow

1. **Data Collection**

   * Dataset containing energy consumption readings

2. **Data Preprocessing**

   * Handle missing values
   * Convert datetime format
   * Clean dataset

3. **Feature Engineering**

   * Extract hour, day, month
   * Create lag feature (previous consumption)

4. **Model Training**

   * Split data into training and testing
   * Train Random Forest model

5. **Model Evaluation**

   * Evaluate using MAE and R² score

6. **Model Saving**

   * Save trained model as `model.pkl`

7. **Deployment**

   * Build Streamlit app for real-time prediction

---

##  How to Run the Project

### 1️ Install dependencies

```
pip install -r requirements.txt
```

### 2️ Run the Streamlit app

```
streamlit run app/app.py
```

---

##  Features

* Predict energy consumption in real-time
* User-friendly interface with sliders
* Time-based prediction model
* Lightweight and fast

---

##  Sample Output

The application takes:

* Hour
* Day
* Month
* Previous energy consumption

 Outputs predicted energy usage instantly.

---

##  Future Enhancements

* Add weather data (temperature, humidity)
* Use advanced models (LSTM, XGBoost)
* Deploy online (Streamlit Cloud)
* Add data visualization dashboard

---

##  Results

* Model successfully predicts energy consumption
* Works efficiently with time-based features
* Provides real-time predictions via web interface

---

##  Conclusion

EnergySaver demonstrates how machine learning can be applied to real-world problems like energy management. By analyzing historical data and predicting future usage, it helps improve efficiency and supports smarter decisions.

---

##  Acknowledgement

This project was developed as part of a data science learning initiative, inspired by real-world energy consumption challenges.

---

##  Author

**Muthukumaraa**

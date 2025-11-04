
# Public Transport Passenger Analysis & Forecasting using Prophet

This project performs **Exploratory Data Analysis (EDA)** and **time-series forecasting** on public transport passenger data, including routes like **Local Route, Rapid Route, Light Rail, School, and Other services**. The goal is to understand seasonal trends, detect anomalies (such as COVID impact), and forecast the next 7 days of passenger numbers using **Facebook Prophet**.

---

## 📂 Project Structure

```
📁 Project Folder
 ┣ 📄 Data_Passangers.csv
 ┣ 📄 analysis_forecast.py
 ┗ 📄 README.md
```

---

## ✅ Key Features

| Feature | Description |
|--------|------------|
| 📌 Data cleaning & preprocessing | Handles date format & missing values |
| 📊 Statistical summary | Summary tables & dataset info |
| 📉 EDA Visualizations | Histograms, boxplots, scatter plots, correlation heatmap |
| 🔍 Outlier detection | IQR-based detection on “Other” route |
| 📆 Monthly trend analysis | Seasonal patterns & long-term trends |
| 🦠 COVID impact isolation | Pre/post pandemic visual comparison |
| 🔮 Prophet forecasting | Predicts passenger counts for next 7 days |
| 🧹 Optimized code | No redundancy, structured flow |

---

## 🛠️ Technologies Used

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Facebook Prophet  

---

## 🚀 How to Run

### 1️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn prophet
```

### 2️⃣ Add your dataset

Ensure file name is:  

```
Data_Passangers.csv
```

### 3️⃣ Run the script

```bash
python analysis_forecast.py
```

---

## 📈 Forecast Output

You will get:

- Forecast values (`yhat`, `yhat_upper`, `yhat_lower`)
- Passenger trend plots
- 7‑day future prediction table

---

## 📌 Future Scope

- Add ARIMA/SARIMA comparison
- Build dashboard using Streamlit/Plotly
- Add live API feed for real‑time forecasting
- Deploy model as web application

---

## 👤 Author

**Sanjay**

---

⭐ *If you found this project useful, consider giving it a star!* ⭐

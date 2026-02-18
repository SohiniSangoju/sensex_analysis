# 📊 Stock Market Analysis & Visualization: Unveiling Sensex Trends

This project analyzes **NSE Sensex stock data** and provides insightful **interactive visualizations** using **Pandas**, **Plotly**, and **Dash**.  

It focuses on trends in stock prices, volumes, turnovers, and seasonal behavior across multiple years — helping investors and analysts uncover meaningful patterns in the Indian stock market.

---

## 🚀 Features

- ✅ **Data Cleaning & Preprocessing** – Handling missing values, formatting dates, preparing datasets  
- ✅ **Exploratory Data Analysis (EDA)** – Statistical summary and descriptive insights from 40K+ records  
- ✅ **Interactive Visualizations with Plotly & Dash**:
  - 📈 Stock Price Trends over time (for all stocks & top 5)  
  - 📦 Daily Price Range distribution (Boxplots)  
  - 🔥 Heatmaps of trading volumes  
  - 📊 Percentage Price Change scatter plots  
  - 📉 Consistent Growth / Decline trends (CAGR visualization)  
  - 📑 Deliverable vs Non-Deliverable Volumes  
  - 💰 Average Turnover by Stock  
  - 📆 Seasonality in stock prices & volumes  
  - 📦 Distribution of Trading Volumes  
- ✅ **Dash Web App** – Explore all charts interactively in one place  

---

## 🛠️ Tech Stack

- **Language**: Python 🐍  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `plotly.express`, `plotly.graph_objects`, `dash`  
- **Dataset**: NSE Sensex stock data (`nse_sensex.csv`)  

---

## 📂 Project Structure
```bash
├── nse_sensex.csv # Dataset (40K+ rows)
├── app.py # Main Dash application
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/SohiniSangoju/sensex_analysis.git
cd sensex_analysis
```
Install dependencies:
```bash
pip install -r requirements.txt
```

Run the Dash app:
```bash
python app.py
```

Open your browser and visit:
```bash
http://127.0.0.1:8050/
```
## 📊 Sample Visualizations

- 📈 Stock Price Trends Over Time  
- 🔥 Trading Volume Heatmap  
- 📑 Deliverable vs Non-Deliverable Volume  
- 📆 Seasonality in Monthly Prices & Volumes  

_All visualizations are interactive: zoom, filter, hover, etc._  

---

## 📌 Use Cases

- 🔍 **Investors** – Track stock performance over time  
- 📈 **Analysts** – Spot seasonal & market-wide patterns  
- 🧑‍💻 **Learners** – Practice EDA, visualization, Dash app development  

---

## 👩‍💻 Author

- **Sohini Sangoju**  

---
## 🔗 Colab Link
[Open in Colab](https://colab.research.google.com/drive/1GYVNEDEZHPPdgjbI2KYPFKnQQJsiuyVW)

## ⭐ Future Enhancements

- 📡 Add real-time stock data via APIs  
- 📊 Include technical indicators (RSI, MACD, etc.)  
- ☁️ Deploy app publicly (Heroku, Render, etc.)  
- 🔎 Add user filters (select stocks, timeframe, etc.)

  

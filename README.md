📊 Stock Market Analysis \& Visualization: Unveiling Sensex Trends



This project analyzes NSE Sensex stock data and provides insightful interactive visualizations using \*\*Pandas\*\*, \*\*Plotly\*\*, and \*\*Dash\*\*.  

It focuses on trends in stock prices, volumes, turnovers, and seasonal behavior across multiple years — helping investors and analysts uncover meaningful patterns in the Indian stock market.



---



\## 🚀 Features



\- ✅ \*\*Data Cleaning \& Preprocessing\*\* – Handling missing values, formatting dates, preparing datasets.  

\- ✅ \*\*Exploratory Data Analysis (EDA)\*\* – Statistical summary and descriptive insights from 40K+ records.  

\- ✅ \*\*Interactive Visualizations with Plotly \& Dash\*\*:  

&nbsp; - 📈 Stock Price Trends over time (for all stocks \& top 5)  

&nbsp; - 📦 Daily Price Range distribution (Boxplots)  

&nbsp; - 🔥 Heatmaps of trading volumes  

&nbsp; - 📊 Percentage Price Change scatter plots  

&nbsp; - 📉 Consistent Growth / Decline trends (CAGR visualization)  

&nbsp; - 📑 Deliverable vs Non-Deliverable Volumes  

&nbsp; - 💰 Average Turnover by Stock  

&nbsp; - 📆 Seasonality in stock prices \& volumes  

&nbsp; - 📦 Distribution of Trading Volumes  

\- ✅ \*\*Dash Web App\*\* – Explore all charts interactively in one place.



---



\## 🛠️ Tech Stack



\- \*\*Language\*\*: Python 🐍  

\- \*\*Libraries\*\*: `pandas`, `numpy`, `matplotlib`, `plotly.express`, `plotly.graph\_objects`, `dash`  

\- \*\*Dataset\*\*: NSE Sensex stock data (`nse\_sensex.csv`)



---



\## 📂 Project Structure



├── nse\_sensex.csv # Dataset (40K+ rows)

├── app.py # Main Dash application

├── requirements.txt # Python dependencies

└── README.md # Project documentation





---



\## ⚙️ Installation



Clone the repository:

```bash

git clone https://github.com/SohiniSangoju/sensex\_analysis.git

cd sensex\_analysis

```



install dependencies:

```bash

pip install -r requirements.txt

```



Run the Dash app:

```bash

python app.py

```



Open your browser and visit:

👉 http://127.0.0.1:8050/



📊 Sample Visualizations



📈 Stock Price Trends Over Time



🔥 Trading Volume Heatmap



📑 Deliverable vs Non-Deliverable Volume



📆 Seasonality in Monthly Prices \& Volumes



All visualizations are interactive: zoom, filter, hover, etc.



📌 Use Cases



🔍 Investors – Track stock performance over time



📈 Analysts – Spot seasonal \& market-wide patterns



🧑‍💻 Learners – Practice EDA, visualization, Dash app development



👩‍💻 Author - Sohini Sangoju



⭐ Future Enhancements



Add real-time stock data via APIs



Include technical indicators (RSI, MACD, etc.)



Deploy app publicly (Heroku, Render, etc.)



Add user filters (select stocks, timeframe, etc.)


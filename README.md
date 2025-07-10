# 📈 Stock Automation using LLM + News Sentiment

This project is an experimental AI-driven stock analysis agent that leverages financial data, LLMs, and Google Search to evaluate stock buy/sell decisions based on real-time sentiment and data signals.

---

## 🧠 Project Overview

The goal of this project is to assist in **automated stock decision-making** by integrating:

- 📊 **Historical stock data** from `yfinance`  
- 🧠 **News sentiment analysis** using LLMs (via OpenAI)  
- 🔎 **Real-time news search** using Google Search API  
- 🤖 **Buy or Sell recommendations** based on positive/negative media tone

---

## 🧩 Architecture

[ yfinance ] → fetch historical data
↓
[ Google Search ] → scrape real-time news
↓
[ OpenAI API ] → analyze sentiment (positive/neutral/negative)
↓
[ Decision Engine ] → output BUY / SELL decision

---

## ⚙️ Features

- Fetches **up-to-date financial data** for any stock symbol
- Scrapes the latest news headlines and summaries
- Uses an LLM to evaluate the **sentiment of each article**
- Aggregates sentiment results to output a simple **Buy / Sell recommendation**

---

## ❗ Paused Development Areas

- ❌ Price prediction model (planned via time series forecasting + sentiment scoring) is currently paused
- ✅ Focus is currently on improving news filtering quality and LLM sentiment evaluation accuracy

---

## 🛠️ Tech Stack

- Python  
- yfinance  
- Google Search API / SerpAPI  
- OpenAI GPT API  
- Pandas, Matplotlib

---

## 📌 Future Plans

- Integrate price forecasting module (LSTM/Prophet-based)
- Improve sentiment scoring calibration with labeled datasets
- Build Streamlit interface for user-friendly interaction

---

## 🧑‍💻 Author

Hyun Jun Lee (이현준)  
📫 hyunjun960214@gmail.com  
🌐 [GitHub](https://github.com/hjjunl)  
🌐 [LinkedIn](https://www.linkedin.com/in/hyunjun-lee-a37448212/)

---

## ⚠️ Disclaimer

This project is for research and educational purposes only. It is **not** financial advice.

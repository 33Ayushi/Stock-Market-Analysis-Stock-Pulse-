# 📈 Stock Market Analysis – Stock Pulse

🔗 **Live Demo:** https://stock-market-analysis-stock-pulse.vercel.app/

---

## 🚀 Project Overview

**Stock Pulse** is a web-based stock market analysis platform that allows users to:

* 🔍 Search for stocks
* 📊 View real-time price charts
* 📈 Analyze stock trends
* 🕒 Explore historical data
* 💡 Get insights into stock performance

👉 Example: A user searches for **TCS** or **Reliance**, and the platform displays charts, trends, and analytics.

---

## 🎯 Project Goal

The goal of this project is to build an interactive and user-friendly platform where users can easily analyze stock market data and make informed decisions.

---

## 🛠️ Tech Stack

### Frontend

* Next.js (React Framework)
* Tailwind CSS (UI Styling)
* Recharts / Chart.js (Data Visualization)

### Backend

* Node.js
* Express.js

### Data Sources

* Alpha Vantage API
* Yahoo Finance API
* Finnhub API

### Database

* PostgreSQL
  or
* MongoDB

---

## 🧩 System Architecture

```
User
 ↓
Frontend (Next.js / React)
 ↓
Backend API (Node.js + Express)
 ↓
Stock Data API
 ↓
Database
```

### Explanation

| Layer        | Role                  |
| ------------ | --------------------- |
| Frontend     | User Interface        |
| Backend      | Business Logic / APIs |
| External API | Stock Data Fetching   |
| Database     | Store User Data       |

---

## 🌐 Website Pages

### 🏠 Dashboard

* Market summary
* Top gainers & losers
* Market indices

**Example:**

* NIFTY 50 ↑ 0.75%
* SENSEX ↑ 0.60%

---

### 🔎 Stock Search Page

* Search any stock
* View:

  * Company name
  * Current price
  * Daily change

---

### 📊 Stock Analysis Page

* Detailed analytics:

  * Price chart
  * Historical data
  * Moving averages
  * Volume

**Example:**

* Stock: TCS
* Price: ₹3950
* Trend: Bullish

---

### ⭐ Watchlist Page

* Save and track favorite stocks

**Example:**

* TCS
* Reliance
* Infosys

---

### 📰 News & Insights Page

* Latest stock news
* Sentiment analysis

**Example:**

* Reliance announces investment
* Sentiment: Positive

---

## 🗄️ Database Design

### Users Table

```
users
------
id
name
email
password
```

### Watchlist Table

```
watchlist
---------
id
user_id
stock_symbol
```

### Stock History (Optional)

```
stock_prices
------------
id
symbol
date
open
close
high
low
volume
```

---

## 🔌 Backend APIs

| Feature          | Endpoint                        |
| ---------------- | ------------------------------- |
| Get Stock List   | GET /api/stocks                 |
| Search Stock     | GET /api/stocks/:symbol         |
| Historical Data  | GET /api/stocks/:symbol/history |
| Add to Watchlist | POST /api/watchlist             |
| Get Watchlist    | GET /api/watchlist              |

---

## 🤖 Unique Features

### 📈 AI Trend Analysis

* Detects:

  * Bullish / Bearish trend
  * Confidence score
  * Reasoning

---

### 📰 News Sentiment Analysis

* Analyzes stock-related news

**Example:**

* Positive: 70%
* Negative: 10%
* Neutral: 20%

---

### 💼 Portfolio Analyzer

* Analyze investments

**Example:**

* TCS ₹20,000
* Reliance ₹15,000

**Output:**

* Risk Level
* Diversification Score

---

## ✅ MVP (Minimum Viable Product)

The first version includes:

* ✔️ Stock search
* ✔️ Price chart
* ✔️ Historical data
* ✔️ Basic dashboard

---

## 🎬 Demo Flow

1. User searches for a stock
2. System fetches data from API
3. Backend processes data
4. Frontend displays charts

**Example:**

* Search: TCS
* View chart
* Analyze trend
* Add to watchlist

---

## 📌 Future Enhancements

* User authentication
* Real-time updates
* Advanced AI predictions
* Portfolio tracking dashboard

---

## 👩‍💻 Author

**Ayushi Katiyar**

---

## ⭐ If you like this project
<img width="1832" height="921" alt="image" src="https://github.com/user-attachments/assets/5f12d3da-96dd-4442-ac56-12bdf9b92693" />


Give it a ⭐ on GitHub and share it 🚀

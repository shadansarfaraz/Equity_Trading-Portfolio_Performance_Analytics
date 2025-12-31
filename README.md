# 📊 Equity Trading & Portfolio Performance Analytics

An end-to-end **Tableau dashboard project** built on a real-world **equity trading and portfolio management dataset**.  
The project provides actionable insights into **market trends, trading activity, portfolio performance, and realized P&L** using a well-structured relational data model.

---

## 🧠 Project Overview

This project simulates a **capital markets analytics use case** where stakeholders require:
- Market trend analysis
- Trading efficiency monitoring
- Portfolio performance evaluation
- Executive-level performance summaries

The solution is built using **Tableau relationships** to handle **multiple fact tables** while preserving data grain and accuracy.

---

## 🛠 Tools & Technologies

- **Tableau Desktop / Tableau Public**
- **Microsoft Excel** (Data Source)
- **GitHub** (Version Control & Documentation)

---

## 📂 Dataset Description

The dataset is provided as a **single Excel workbook** containing multiple sheets.

### 🔹 Dimension Tables
| Table Name | Description |
|-----------|------------|
| `dim_company` | Company master data |
| `dim_sector` | Sector classification |
| `dim_exchange` | Stock exchange details |
| `dim_trader` | Trader information |
| `dim_portfolio` | Portfolio & manager details |
| `dim_calendar` | Date & time intelligence |

### 🔹 Fact Tables
| Table Name | Description |
|-----------|------------|
| `fact_daily_prices` | Daily OHLC price & volume data |
| `fact_orders` | Orders placed |
| `fact_trades` | Executed trades |
| `fact_positions_snapshot` | Portfolio holdings by date |
| `fact_trades_pnl_kpi` | Realized P&L and return metrics |
| `fact_dividends` | Dividend events |
| `fact_splits` | Stock split events |

---

## 🧩 Data Model Design

- Implemented using **Tableau Relationships** (no physical joins)
- **Hub-and-spoke architecture** with `dim_company` as the central dimension
- Calendar linked at the **fact table level**
- Multiple fact tables kept independent to avoid duplication

**Why Relationships?**
- Accurate aggregations
- Correct handling of different grains
- Scalable and enterprise-grade modeling

---

## 📊 Dashboards Overview

### 1️⃣ Market Analysis Dashboard
**Purpose:** Analyze stock price trends, trading volumes, and sector/exchange performance.

**Key KPIs**
- Total Market Capitalization
- Average Stock Price
- Total Trading Volume
- % Volume Suspect

**Visuals**
- Price trend over time
- Volume by sector
- Exchange vs sector heatmap

---

### 2️⃣ Trading Activity Dashboard
**Purpose:** Monitor order execution efficiency and trader performance.

**Key KPIs**
- Total Orders
- Total Trades
- Order Fill Rate
- Buy vs Sell Quantity

**Visuals**
- Buy vs Sell trends
- Orders vs Trades over time
- Trades by trader

---

### 3️⃣ Portfolio Performance & P&L Dashboard
**Purpose:** Evaluate portfolio profitability and investment performance.

**Key KPIs**
- Realized Profit
- Return %
- Win Rate
- Total Fees

**Visuals**
- P&L by portfolio
- Top winning stocks
- Return % distribution

---

### 4️⃣ Executive Summary Dashboard
**Purpose:** Provide leadership with a high-level performance snapshot.

**Highlights**
- Total Market Value
- Total Realized P&L
- Best & worst performing portfolios/sectors
- Key performance trends

---

## 📐 Dashboard Design & Formatting

- Clean, executive-friendly layout
- KPI tiles with consistent formatting
- Financial color coding (green = profit, red = loss)
- Interactive filters and tooltips
- Optimized for desktop viewing

---

## 🚀 Key Learnings

- Designing multi-fact Tableau data models
- Implementing enterprise-level financial dashboards
- Applying data visualization best practices
- Translating complex data into actionable insights

---

## 📌 How to Use

1. Open Tableau Desktop
2. Connect to the provided Excel workbook
3. Build relationships as per the data model
4. Open the dashboard worksheets
5. Explore insights using interactive filters

---

## 👩‍💻 Author

**Shadan Sarfaraz**  
Data Analyst | Tableau | SQL | Power BI  

📧 Email: shadansarfaraz01@gmail.com  
📍 Bangalore, India

---

## ⭐ If you like this project
Feel free to ⭐ the repository and share feedback!
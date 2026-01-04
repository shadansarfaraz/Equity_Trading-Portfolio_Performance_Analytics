# 📊 Equity Trading & Portfolio Performance Analytics

A Tableau-based analytics project designed to deliver **market insights, trading efficiency metrics, and portfolio performance evaluation** using real-world equity trading data.

---

## ⭐ STAR Project Summary

---

### 🟢 S — Situation

Financial stakeholders required a **comprehensive analytics solution** to monitor:
- Stock market trends across sectors and exchanges
- Trading activity and order execution efficiency
- Portfolio-level profitability and risk
- Executive-level performance insights

The data was provided in a **single Excel workbook with multiple sheets**, containing **multiple fact tables at different grains**, making accurate modeling and visualization critical.

---

### 🟡 T — Task

As the **Data Analyst**, my responsibility was to:
- Design a **scalable Tableau data model** handling multiple fact tables
- Build **interactive dashboards** for different stakeholder levels
- Ensure **accurate aggregations** and financial KPIs
- Present insights in a **clear, executive-friendly format**

---

### 🔵 A — Action

I performed the following key actions:

#### 📐 Data Modeling
- Implemented **Tableau Relationships** instead of physical joins
- Designed a **hub-and-spoke model** with `dim_company` as the central dimension
- Linked calendar data at the **fact table level** to preserve data grain
- Maintained independent fact tables for trades, orders, prices, and P&L

#### 📊 Dashboard Development
- Built **four interactive dashboards**:
  1. Market Analysis
  2. Trading Activity
  3. Portfolio Performance & P&L
  4. Executive Summary
- Designed KPI tiles for financial metrics such as:
  - Market Capitalization
  - Realized Profit
  - Return %
  - Order Fill Rate
- Applied financial visualization best practices:
  - Consistent color coding (green = profit, red = loss)
  - Clean layouts and minimal clutter
  - Dynamic filters and tooltips

#### 🎨 Formatting & Usability
- Used professional dashboard sizing and spacing
- Optimized number formatting (M/B, currency, percentages)
- Added interactive filters by date, portfolio, trader, sector, and exchange

---

### 🟣 R — Result

- Delivered a **production-ready Tableau dashboard suite**
- Enabled stakeholders to:
  - Identify top-performing portfolios and sectors
  - Monitor trading efficiency and execution quality
  - Analyze profitability and cost impact
- Created a **reusable and scalable data model** suitable for future datasets
- Improved dashboard clarity and decision-making readiness

---

## 🛠 Tools & Technologies

- **Tableau Desktop / Tableau Public**
- **Microsoft Excel**
- **GitHub**

---

## 📂 Dataset Overview

### Dimension Tables
- dim_company
- dim_sector
- dim_exchange
- dim_trader
- dim_portfolio
- dim_calendar

### Fact Tables
- fact_daily_prices
- fact_orders
- fact_trades
- fact_positions_snapshot
- fact_trades_pnl_kpi
- fact_dividends
- fact_splits

---

## 🚀 Key Skills Demonstrated

- Tableau Data Modeling (Relationships)
- Financial & Trading Analytics
- Dashboard Design & Storytelling
- KPI Definition & Visualization
- Business Insight Communication

---

## 📌 How to Use

1. Connect Tableau to the Excel workbook
2. Build relationships as per the data model
3. Open the dashboard worksheets
4. Explore insights using interactive filters

---

## 👩‍💻 Author

**Shadan Sarfaraz**  
Data Analyst | Tableau | SQL | Power BI  

📧 Email: shadansarfaraz01@gmail.com  
📍 Bangalore, India

---

⭐ If you find this project insightful, feel free to star the repository!
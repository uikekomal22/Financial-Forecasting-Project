## Project 1: Nestlé India Financial Forecasting – Forecast Analysis (2027–2029)

* **Objective:** Analyze Nestlé India's historical financial statements to project future corporate revenue velocities, track operational expense thresholds, and assess long-term profitability metrics.
* **Tools Used:** Python (Jupyter Notebook via Anaconda Navigator), Microsoft Excel, Power BI Desktop.
* **Methodology:** Executed rigorous historical data cleaning, trend identification, stationarity validation (ADF testing), and seasonality analysis on past income statement line items.
* **Key Outcome:** Developed an end-to-end predictive Time Series framework that generates a comprehensive 3-year financial outlook forecasting **Revenue, Expenses, Profit Before Tax (PBT), and Profit After Tax (PAT)** for the fiscal years **2027, 2028, and 2029**.

---

### Project Architecture & Implementation Pipeline

#### 1. Python Algorithmic Core
* Developed an **Autoregressive Integrated Moving Average (ARIMA)** script to model Nestlé India's historical quarterly and annual sales cycles.
* Applied optimal parameter tuning $(p, d, q)$ to capture baseline momentum, smooth out unexpected market shocks, and extrapolate raw mathematical projections for top-line revenue and core operational cost drivers.

#### 2. Excel Financial Modeling
* Ingested the raw ARIMA Python projections into a structured, formula-driven corporate financial model.
* Engineered automated dynamic schedules to calculate cost of goods sold (COGS), variable marketing expenditures, corporate tax provisions, **Profit Before Tax (PBT)**, and final **Profit After Tax (PAT)** margins.

#### 3. Power BI Executive Dashboard
* Designed an interactive, forward-looking executive dashboard titled **"Nestlé India Financial Forecasting - Forecast Analysis (2027–2029)"**.
* Built key data visualizations including multi-year trend lines, dynamic expense-to-revenue ratio indicators, and multi-scenario toggle switches to let stakeholders visualize aggressive, baseline, and conservative growth paths.

---

### 3-Year Strategic Forecast Summary Matrix

| Financial Metric (INR Cr) | FY 2027 Forecast | FY 2028 Forecast | FY 2029 Forecast | Strategic Operational Guidance |
| :--- | :--- | :--- | :--- | :--- |
| **Gross Revenue** | *[Insert Value]* | *[Insert Value]* | *[Insert Value]* | Tracks top-line consumer demand and price volume velocity. |
| **Operating Expenses** | *[Insert Value]* | *[Insert Value]* | *[Insert Value]* | Highlights critical inflation boundaries and procurement thresholds. |
| **Profit Before Tax (PBT)** | *[Insert Value]* | *[Insert Value]* | *[Insert Value]* | Measures raw operational efficiency before tax regulations. |
| **Profit After Tax (PAT)** | *[Insert Value]* | *[Insert Value]* | *[Insert Value]* | Represents net corporate earnings available for reinvestment/dividends. |

***Strategic Business Insight Derived:*** The predictive model isolates high-growth quarters where Nestlé India can aggressively scale supply chain inventory. It also identifies accelerating expense thresholds, signaling precisely when management should deploy cost-containment measures to safeguard net margins.

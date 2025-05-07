# Connecticut Real Estate Investing Strategy

## Table of Contents
- [Project Overview](#project-overview)
- [Tools & Techniques](#tools--techniques)
- [Insights](#insights)
  - [Seasonal Trends](#seasonal-trends)
  - [Residential Type Volatility](#residential-type-volatility)
  - [Economic Shifts](#economic-shifts)
  - [Opportunistic Investments](#opportunistic-investments)
- [Recommendations](#recommendations)
- [Data Limitations](#data-limitations)

---

##  Project Overview
This project analyzes over **1 million Connecticut property sales from 1999 to 2023** to uncover strategic insights for real estate investment. Using financial and statistical methods like **CAGR, volatility analysis, and time series trends**, it identifies where, when, and what to invest in for optimal returns.

**Key Insights:**
- **Best Buy Season:** Winter months (Jan–Feb) offer **20–30% lower median prices** than peak summer
- **Property Risk Profile:** **Condos have 40.5% higher volatility** than single-family homes — suitable for risk-tolerant investors
- **Top Growth Towns:** Windsor and Franklin outperformed state averages with **CAGR of 9–11%**
- **Economic Resilience:** Prices dropped significantly during 2008 and COVID-19 but rebounded within 24 months

---

##  Tools & Techniques
- **Python (Pandas, NumPy, Matplotlib):** Time series analysis, CAGR & volatility calculations, town segmentation
- **Excel:** Data cleaning, validation, pivot table summaries
- **Metrics Used:**
  - **CAGR** — long-term town-level growth
  - **Price Volatility** — risk segmentation by property type
  - **Monthly Trend Analysis** — seasonality-driven timing
  - **Economic Event Analysis** — shifts during 2008 & COVID-19

---

##  Insights

###  Seasonal Trends
- June–August = peak sales and median pricing
- Jan–Feb = best time to buy (**~12% lower pricing**)

![Monthly Historical Trends](sale_volume_dual.png)

###  Residential Type Volatility
- Condos: **40.5% volatility** — high risk/reward
- Single-family homes: lower volatility, more stability

![Residential Type CAGR](residential_best.png)  
![Residential Type Volatility](residential_volatility.png)

###  Economic Shifts
- Price dips in 2008 and 2020 due to recession/pandemic
- Rebounded within **12–24 months**, proving recovery strength

![Price Volatility Over Time](volatility_shift.png)

###  Opportunistic Investments
- **Windsor** and **Franklin** showed **10.5–11% CAGR** over 20+ years
- Smaller towns outperforming larger cities with lower competition

![Top 10 Towns CAGR](town_cagr.png)

---

##  Recommendations
- **Buy in Off-Season**: Jan–March prices are **~12% lower** than peak season
- **Diversify Risk**: Don’t over-index in condos unless balanced with stable assets
- **Target Emerging Towns**: Focus on Windsor, Franklin, and similar towns with high CAGR
- **Monitor Recessions**: Temporary dips ≠ long-term damage — use them to enter undervalued markets

---

##  Data Limitations
- Data ends at 2023; recent market shifts not captured
- No inclusion of mortgage rates, rental yield, or macroeconomic overlays
- Some rural town records had missing values or inconsistencies

---
---

To view the full Python analysis, [click here.](https://github.com/amontaywelch/ct_real_estate/blob/main/CTrealestate%20(2).ipynb)
Check out my [LinkedIn!](https://www.linkedin.com/in/amontaywelch/)

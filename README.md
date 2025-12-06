# Data Procesing
**Research Question**  
> *Which companies and sectors contributed most to the S&P 500’s overall performance during the first half of 2025, and how did volatility and trading activity influence these movements?*

---

## 🎯 Objectives
- Analyze daily **open**, **close**, and **volume** data for **503 S&P 500 companies** (Jan–Jun 2025)
- Engineer performance metrics:
  - Daily & cumulative returns  
  - Volatility  
  - Average dollar volume  
- Estimate market impact through a **weighted contribution metric**
- Identify top-performing sectors and companies
- Understand whether volatility and liquidity contributed to outperformance

---

## 🧮 Methodology

| Step | Description |
|------|-------------|
| **Data Processing** | Cleaning & aggregating the dataset |
| **Feature Engineering** | Compute returns, volatility, and liquidity |
| **Impact Estimation** | Weighted contribution = *Cumulative Return × Avg. Dollar Volume* |
| **Modeling** | Linear regression on return drivers (risk, liquidity, sector) |

---

## 🔍 Key Preliminary Insights
- 🚀 Performance leadership was **highly concentrated** in a small set of stocks  
- 🧠 **Information Technology sector** dominated index gains  
- 💸 Higher **dollar volume** correlated with greater market impact  
- 📉 Volatility contributed only **weak predictive power**, consistent with short-term market noise  

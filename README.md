# 📈 MLQuant: Stock Return Forecasting & Portfolio Optimization  

*Stock Return Forecasting & Portfolio Optimization using ML + Quantitative Finance Models*  

---

## 📌 Project Overview  
This project focuses on forecasting stock returns and optimizing portfolios by combining **machine learning models** with **quantitative finance techniques**.  
The goal is to enhance investment decisions through predictive modeling and risk-aware portfolio allocation strategies.  

---

## 📊 Dataset  
- **Historical stock market data (10+ years)**  
- Added **20+ technical indicators** (RSI, MACD, Bollinger Bands, volatility, etc.)  
- Features: engineered indicators + lagged returns  
- Target: next-day stock return  

---

## 🔬 Approach  

### 1. Data Pipeline & Feature Engineering  
- Collected and processed 10+ years of stock price data  
- Added 20+ technical indicators (momentum, volatility, trend, mean-reversion signals)  
- Built features using lag windows and rolling statistics  

### 2. Model Training  
- Trained **XGBoost models** for next-day return forecasting  
- Compared performance with baseline models  
- Conducted feature importance analysis for interpretability  

### 3. Portfolio Optimization  
- Applied forecasts in:  
  - **Markowitz Efficient Frontier**  
  - **Conditional Value-at-Risk (CVaR)**  
  - **Black-Litterman Model**  

### 4. Evaluation  
- Backtested on multiple time horizons  
- Evaluated using **Sharpe ratio**, portfolio return, and risk-adjusted performance  

---

## 🏆 Results  
- Achieved **22% Sharpe ratio improvement** compared to equal-weight portfolios in backtests  
- Demonstrated a **scalable ML-powered investment workflow** for stock return forecasting & allocation  

---

## 📂 Repository Contents  
- `MLQuant.ipynb` → Jupyter Notebook with full code & analysis  
- `README.md` → Project documentation (this file)  

---

## 👤 Author  
**Vashistha Pankaj**  
- Email: *vashistha22@iitk.ac.in*  
- LinkedIn: *[(https://www.linkedin.com/in/vashistha021/)]*  

# 🛒 Retail Sales Time Series Forecasting (Elevvo Pathways)

This project explores and forecasts **retail sales time series data**, uncovering seasonal trends, holiday effects, and store-level patterns.  
It is developed as part of **Elevvo Pathways** and is fully available on GitHub.

---

## 📊 Project Overview
- **Dataset Source:** Walmart retail dataset (features, stores, train, test)  
- **Goal:**  
  - Preprocess and merge multiple raw datasets  
  - Perform exploratory data analysis (EDA)  
  - Analyze **seasonality, trends, and holiday effects**  
  - Train time series forecasting models (baseline + advanced)  
- **Deliverables:**  
  - Clean merged dataset  
  - Jupyter Notebooks with analysis  
  - Forecasting results & visualizations  
  - Conda environment (`environment.yml`)  

---

## 🛠 Tools & Libraries
- **Python:** pandas, numpy, matplotlib, seaborn, statsmodels  
- **Environment:** Conda (`retail-timeseries`)  
- **Deliverables:** notebooks (`.ipynb`), dataset (`.csv`), environment (`.yml`)  

---

## 🔑 Key Steps
1. **Data Preparation**  
   - Merged features, stores, train, and test datasets  
   - Handled missing values in markdowns, CPI, and unemployment  
   - Converted dates into datetime format  

2. **Exploratory Data Analysis (EDA)**  
   - Weekly aggregated sales trend (2010–2012)  
   - Seasonal decomposition (trend, seasonal, residual)  
   - Holiday vs. Non-Holiday sales analysis  
   - Store type and size impact on sales  

3. **Forecasting**  
   - Baseline seasonal decomposition model  
   - Planned extensions: ARIMA/SARIMA, Prophet, ML approaches  

---

## 📌 Key Insights
1. Sales exhibit **strong weekly and yearly seasonality**.  
2. **Holidays drive major spikes** in weekly sales.  
3. **Store type and size** correlate with overall sales volume.  
4. Markdown promotions show inconsistent but important effects.  

---

## ⚙️ Setup Instructions  

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/retail_timeseries_project.git
cd retail_timeseries_project

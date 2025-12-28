# Walmart Sales Analysis and Forecasting

This project performs an in-depth analysis of Walmart weekly sales data to
understand the impact of economic and seasonal factors on sales and to forecast
future demand using predictive modeling techniques.

---

## 📊 Dataset Description

The dataset contains weekly sales data for multiple Walmart stores across the
country.

**Number of Records:** 6435  
**Number of Features:** 8  

### Features:
- **Store**: Store number  
- **Date**: Week of sales  
- **Weekly_Sales**: Sales for the given store in that week  
- **Holiday_Flag**: Indicates whether the week includes a holiday  
- **Temperature**: Temperature on the day of sale  
- **Fuel_Price**: Cost of fuel in the region  
- **CPI**: Consumer Price Index  
- **Unemployment**: Unemployment rate  

---

## 🔍 Exploratory Data Analysis (EDA)

The following analysis was performed:
- Handling missing values using mean imputation
- Statistical analysis of weekly sales
- Outlier detection using box plots
- Correlation analysis between sales and economic indicators

---

## 📈 Key Insights

- Weekly sales are negatively affected by higher unemployment rates.
- Clear seasonal trends are observed, with peak sales during November and December.
- Temperature has a minimal impact on weekly sales.
- Higher CPI slightly reduces customer purchasing power and sales.
- Significant performance differences exist between stores.
- Top-performing and worst-performing stores were identified using historical data.

---

## 🔮 Sales Forecasting

- Time series forecasting was performed using the **ARIMA model**.
- Sales were forecasted for the **next 12 weeks** for individual stores.
- Forecasting helps in better inventory planning and demand management.

---

## 🛠 Tools and Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels (ARIMA)

---

## 📌 Conclusion

This analysis provides valuable insights into sales patterns, economic impacts,
and seasonal trends, enabling data-driven inventory and supply chain decisions.
The forecasting model supports proactive planning for future demand.

---

## 📁 Project Files

- `walmart_sales_analysis.ipynb` – Main analysis and forecasting notebook  
- `Walmart DataSet.csv` – Dataset used for analysis  
- `README.md` – Project documentation  

---


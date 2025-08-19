# Stock Analysis Dashboard 📈  

## 📌 Overview  
The **Stock Analysis Dashboard** is an interactive business intelligence solution that provides insights into stock performance, price fluctuations, holdings, and global distribution. Built using Power BI, it helps investors, analysts, and portfolio managers track their stock investments with visual clarity and actionable analytics.  

This dashboard enables:  
- Real-time monitoring of **stock prices and gains**.  
- Analysis of **holdings and portfolio distribution**.  
- Country-wise mapping of stocks for **geographical investment analysis**.  
- Comparison of **stock performance trends** across time periods.  

---

## 🚀 Features  
- **Key KPIs at a glance**:  
  - Total Cost: `4.91K`  
  - Total Holdings: `74`  
  - Total Price: `988.89`  

- **Product Price Analysis**:  
  - Bar chart showing stock-wise investment distribution (e.g., SOXX, SMH, AAPL, etc.).  

- **Daily Price and Gain**:  
  - Combination chart with daily stock price vs. gains/losses.  

- **Total Holdings**:  
  - Gauge visualization representing total stock holdings.  

- **QuoteName with Price**:  
  - Pie chart showing stock price share percentages across portfolio.  

- **Closing Price by Date and QuoteName**:  
  - Line chart visualizing stock closing prices over time.  

- **Top Performing Stocks (High Stock Value)**:  
  - Treemap visualization highlighting the highest stock contributions (e.g., SOXX, AAPL, SMH, VNQ).  

- **Country-wise Stock Distribution**:  
  - World map visualization to track geographical stock exposure.  

- **Interactive Filters**:  
  - Filter by **Target, Currency, Type, Industry, and QuoteName** for custom analysis.  

---

## 📊 Insights from the Dashboard  
1. **SOXX and SMH** dominate the portfolio with the largest stock holdings.  
2. Portfolio gains fluctuate daily, with some negative gain days (`-50.77`) and strong positive spikes (`+72.35`).  
3. Stocks like **AAPL, RY.TO, and VNQ** show significant contributions to overall stock performance.  
4. Geographical analysis indicates diversified investments across **North America, Europe, and Asia**.  
5. Treemap analysis reveals **technology sector dominance** in the portfolio.  

---

## 🛠️ Tech Stack  
- **Data Source**: Stock market dataset (CSV/Excel/Live API integration possible)  
- **Data Processing**: Power Query / SQL (for cleaning & transformation)  
- **Visualization Tool**: Microsoft Power BI  
- **Deployment**: Power BI Service / GitHub repository for sharing `.pbix` file and screenshots  

---

## 📂 Project Structure  
```bash
├── data/
│   ├── stock_dataset.csv         # Raw dataset
│   ├── processed_data.csv        # Cleaned dataset for Power BI
├── dashboard/
│   ├── Stock_Analysis.pbix       # Power BI Dashboard file
│   ├── Stock_Analysis.png        # Dashboard screenshot
├── README.md                     # Project documentation

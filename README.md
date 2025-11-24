# 🏨 Hotel Revenue Management Analytics

> Comprehensive revenue optimization system leveraging forecasting, dynamic pricing strategies, and operational insights to maximize hotel profitability

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-SQLite-orange.svg)](https://www.sqlite.org/)
[![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow.svg)](https://powerbi.microsoft.com/)

## 🎯 Project Overview

This analytics suite was developed to address key challenges in hospitality revenue management:
- **Demand Forecasting** - 90-day forward visibility with <6% MAE
- **Revenue Optimization** - Moving average forecasting for seasonal patterns
- **Overbooking Strategy** - Monte Carlo simulation reducing lost revenue by 15%
- **Executive Insights** - Power BI dashboards tracking ADR, RevPAR, and occupancy

**Business Impact**: Simulation shows potential 12% revenue increase (£180K annually for a 200-room hotel)

## 📊 Key Features

### 1. Data Engineering & SQL
- Star schema design with fact and dimension tables
- Optimized queries for hospitality KPIs (ADR, RevPAR, occupancy)
- Date dimension for time-series analysis
- Data quality checks and validation

### 2. Predictive Analytics
- **Moving Average Forecasting**: 90-day demand prediction
- **Seasonal Pattern Recognition**: Peak/off-peak identification
- **Trend Analysis**: Year-over-year performance comparison

### 3. Simulation & Optimization
- **Monte Carlo Simulation**: 10,000 iterations for overbooking strategy
- **Risk Analysis**: No-show probability modeling
- **Revenue Impact**: Quantified financial outcomes

### 4. Business Intelligence
- **Executive Dashboard**: High-level KPIs and trends
- **Forecasting View**: Demand predictions with confidence intervals
- **Operations View**: Daily performance tracking

## 🛠️ Technical Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python 3.9+, SQL |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Power BI |
| **Database** | SQLite |
| **Statistical Modeling** | Moving Average, Monte Carlo Simulation |

## 📈 Results & Insights

### Key Findings

1. **Seasonal Patterns**
   - 35% occupancy increase during summer months (June-August)
   - Weekend demand 22% higher than weekdays
   - Holiday periods show 40% revenue premium

2. **Forecasting Accuracy**
   - Moving average model achieves <6% MAE
   - 90-day forward visibility enables proactive pricing
   - Seasonal adjustments improve prediction by 18%

3. **Overbooking Optimization**
   - Historical no-show rate: 15%
   - Optimal overbooking: 8-10% above capacity
   - Revenue gain: £15K monthly (simulated)

### Sample Visualizations

![Revenue Trends](dashboards/dashboard_screenshots/executive_overview.png)
*Executive dashboard showing year-over-year revenue trends and key metrics*

![Forecast Accuracy](dashboards/dashboard_screenshots/forecasting_view.png)
*90-day demand forecast with actual vs predicted comparison*

## 🚀 How to Run This Project

### Prerequisites
```bash
Python 3.9+
Jupyter Notebook
Power BI Desktop (for dashboard viewing)
```

### Installation
```bash
# Clone repository
git clone https://github.com/YourUsername/hospitality-revenue-analytics.git
cd hospitality-revenue-analytics

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

### Execution Order
1. `01_data_preparation.ipynb` - Clean and prepare data
2. `02_sql_database.ipynb` - Create database and load data
3. `03_analysis_insights.ipynb` - Generate business insights
4. `04_revenue_forecasting.ipynb` - Run forecasting models
5. `05_overbooking_simulation.ipynb` - Execute Monte Carlo simulation
6. Open `power_bi_file.pbix` for interactive dashboards

## 💼 Skills Demonstrated

### Technical Skills
✅ **Data Analysis** - Pandas, NumPy for data manipulation  
✅ **SQL** - Database design, star schema, complex queries  
✅ **Python** - Statistical analysis, forecasting algorithms  
✅ **Data Visualization** - Matplotlib, Seaborn, Power BI with DAX  
✅ **Statistical Modeling** - Time series forecasting, Monte Carlo simulation  

### Business Analysis Skills
✅ **Requirements Analysis** - Defined KPIs based on industry standards  
✅ **Process Mapping** - AS-IS and TO-BE revenue workflows  
✅ **ROI Calculation** - Quantified business impact  
✅ **Stakeholder Communication** - Executive-level visualizations  
✅ **Domain Expertise** - Hospitality revenue management principles  

## 📚 Project Context

**Background**: Built on 1+ year experience in hospitality operations (JW Marriott Houston) and restaurant revenue management (Paprika Bodrum), this project demonstrates end-to-end analytics capabilities suitable for Business Intelligence and Business Analyst roles in the hospitality sector.

**Data Source**: Analysis based on the Hotel Booking Demand dataset (Kaggle), comprising 119,000+ booking records across 2016-2017, including cancellations, market segments, and pricing data.

## 📞 Contact & Portfolio

**Berke Ilgun**  
📧 berke.ilgun.uk@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/berkeilgun/)  
📊 [Portfolio Website](#) *(if you create one)*

## 📝 License

This project is for portfolio demonstration purposes. Data sourced from public Kaggle datasets.

---

⭐ **If you found this project interesting, please consider giving it a star!**

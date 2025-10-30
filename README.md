# 🚗 Car Sales Data Analysis Project

**Tools Used:** SQL, Excel, Julius AI  
**Duration:** October 2025  
**Repository:** https://github.com/Swithin18/car-sales-sql-project

---

## 🎯 Objective
To analyze used car sales data and uncover key insights about pricing, brand performance, and sales trends using SQL and Julius AI dashboards.

---

## 🧩 Dataset
- 10,000+ car sales records  
- Columns include: `year`, `make`, `model`, `trim`, `body`, `transmission`, `state`, `condition`, `odometer`, `color`, `interior`, `seller`, `mmr`, `sellingprice`, `saledate`.  
- Source: Public automotive sales dataset (cleaned for analysis).

---

## 🧼 Data Cleaning (SQL)
- Replaced missing categorical values (`make`, `model`, `transmission`, `color`, `interior`) with `'Unknown'`.  
- Dropped rows with missing critical numeric values like `sellingprice`, `odometer`, and `saledate`.  
- Formatted columns for consistency (e.g., `saledate` → DATE, `sellingprice` → NUMERIC).  
- Ensured relational integrity and checked for duplicates.

---

## 📊 SQL Analysis
- Top-selling car brands and models by state.  
- Average selling price segmented by car condition and model year.  
- Correlation between odometer reading and selling price.  
- Sales trend over time (monthly/seasonal).  
- Transmission type distribution (Automatic vs Manual).

---

## 📈 Julius AI Dashboard Insights

The dashboard visuals were generated using **Julius AI**, an AI-powered analytics tool that automates data visualization and pattern detection.

**Key Visuals**
| Insight | Description |
|----------|--------------|<img width="2000" height="1200" alt="Sale" src="https://github.com/user-attachments/assets/5541357f-087c-4709-a891-155e46a036df" />

| **Top Brands by Sales** | Toyota, Honda, and Ford led overall volume. | 
| **Condition vs Price** | Cars in ‘Excellent’ condition sold for ~22% higher prices. |
| **Odometer vs Price** | Clear negative correlation — price drops after 100K km. |
| **Monthly Sales Trend** | Peak sales between March–June; dip during monsoon months. |
| **Transmission Mix** | 70% of cars sold had automatic transmission. |

---

## 💡 Business Insights
- Focus on vehicles in “Good” or “Excellent” condition to maximize profit margins.  
- Prioritize automatic models for resale; higher turnover and customer preference.  
- Optimize marketing in high-demand months (March–June).  
- Consider dynamic pricing for high-odometer cars to move slower inventory faster.

---

## 🧠 Skills Demonstrated
- Data cleaning & analysis (SQL)  
- AI-based visualization & interpretation (Julius AI)  
- Business problem-solving  
- Insight presentation & storytelling  

---

## 📎 Future Improvements
- Build Power BI dashboard for deeper interactivity.  
- Add a machine learning model to predict selling prices.  
- Automate sales reports using Python or SQL scheduling.

---



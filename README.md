# Car Sales Data Analysis Project

**Tools Used:** PostgreSQL, SQL, Excel (or Power BI)  
**Duration:** [June 2025]  
**Repository Link:** https://github.com/Swithin18/car-sales-sql-project

---

## 🧭 Project Objective  
The aim of this project is to design, implement and analyse a relational database for car sales data, and to extract actionable business insights. Through cleaning, structuring and querying the dataset, the goal is to uncover key trends in pricing, vehicle conditions, sales volume and regional behaviour — enabling data-driven decision-making for stakeholders.

---

## 📂 Dataset  
- Contains over 10,000 car sales records with attributes such as: year, make, model, trim, body, transmission, VIN, state, condition, odometer, colour, interior, seller, MMR (market-median retail), selling price, and sale date.  
- Source: Kaggle dataset
- Columns used: `year`, `make`, `model`, `body`, `transmission`, `condition`, `odometer`, `selling_price`, `sale_date`, etc.

---

## 🧼 Data Cleaning & Preparation (SQL)  
- Removed or imputed missing values for critical fields like `selling_price`, `odometer`, `sale_date`.  
- Standardized categorical fields (make, model, transmission, condition) for consistency.  
- Converted date and numeric formats appropriately (e.g., `sale_date` as DATE, `odometer` as INTEGER).  
- Created derived fields for analysis (e.g., vehicle age = current_year – year_of_manufacture).  
- Ensured referential integrity if using normalization (e.g., separate tables for makes, models, states).

---

## 📊 Exploratory & Analytical Queries  
Using SQL, performed analysis such as:  
- Top selling car makes and models by state.  
- Average selling price by vehicle condition, age and odometer reading.  
- Distribution of transmissions (automatic vs manual) and their impact on selling price.  
- Time series analysis: monthly and yearly sales volume trends.  
- Correlation between odometer reading and selling price, and other key drivers of price.  

---

## 📈 Dashboard & Visual Insights  
The dashboards folder contains visualizations built in Excel (or Power BI) that highlight:  
- Sales volume and revenue by brand & region.  
- Trend line of average selling prices over time.  
- Condition and transmission mix breakdowns.  
- KPI cards: total cars sold, average price, median odometer, etc.  

(images and screenshots available in `dashboards/` folder)

---

## 💡 Key Business Findings  
- **Finding #1:** Vehicles from trusted brands (e.g., Toyota, Honda) consistently show higher selling prices despite higher odometer readings.  
- **Finding #2:** Automatic transmissions sold ~25% faster than manual sticks, suggesting resale preference.  
- **Finding #3:** Condition of the vehicle (Good/Excellent vs Fair/Poor) has a stronger impact on price than age or mileage alone.  
- **Finding #4:** Monthly sales peak around [March-June], indicating a seasonality effect — useful for inventory planning and promotions.  
- **Finding #5:** Vehicles with odometer >100,000 km show steep resale drop, suggesting threshold behaviour.

---

## 🔧 Skills & Tools Covered  
- Relational database schema design & implementation  
- Data cleaning and transformation in SQL  
- Complex query writing, aggregation and grouping  
- Trend, distribution and correlation analyses  
- Data visualization in Excel / Power BI  
- Business insight generation & presentation  



## 📚 Repository Structure  

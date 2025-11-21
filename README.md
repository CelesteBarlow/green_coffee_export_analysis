# Coffee Exports Analysis (2000–2023)

[View the notebook](https://github.com/CelesteBarlow/green_coffee_export_analysis/blob/main/greencoffee-export-analysis.ipynb)

### Data Cleaning • Supply Chain Analytics • Climate & Trade Research

This project analyzes global green coffee exports for the world’s top producing countries (2000–2023).  
It focuses on **data quality validation**, **export volume and price behavior**, and prepares the foundation for integrating **ERA5 climate data** in a second phase.

This work combines my background in **coffee operations & supply chain management** with my training in **data analytics**, and is part of a larger effort to explore how climate variability affects global agricultural trade.

---

## 1. Project Summary

This analysis examines:
- Annual export volumes of green coffee (kg)
- Export value and FOB unit prices (USD/kg)
- Year-over-year volatility and historical market shocks
- Data consistency across multiple sources (FAOSTAT, UN Comtrade)

The primary goal of this phase was to **fully clean, validate, and document** export and price data before introducing climate variables.

---

## 2. Key Achievements

### **✔ Data Extraction & Preparation**
- Filtered a **52M-row FAOSTAT dataset** to isolate:
  - *Coffee, green*  
  - *Export quantity* & *Export value*
  - Top 15 producing countries
- Converted units, standardized price fields, and created:
  - `export_lbs`
  - `cost_per_kg`
  - `cost_per_lb`

### **✔ Data Validation & Corrections**
- Identified and corrected structural errors in:
  - **Uganda (2003)** — FAOSTAT under-reporting corrected using UCDA & Comtrade  
  - **Kenya (2002)** — FAOSTAT mis-scaled value corrected to historical range  
- Confirmed all other large swings reflected **real historical events**, including:
  - 2001 coffee crisis  
  - 2011 Arabica price spike  
  - 2022 frost & climate disruptions  

### **✔ Exploratory Economic Analysis**
- Price distribution analysis across 15 origins  
- Z-score outlier detection  
- Price-volume correlation (supply- vs demand-driven markets)  
- Identified structural differences between:
  - High-quality Arabica exporters  
  - Large-scale Robusta producers  
  - Mixed-market origins  

This phase results in a **clean, historically grounded dataset** ready for climate modeling.

---

## 3. Technical Skills Demonstrated

**Data Engineering & Cleaning**  
- Large dataset handling (50M+ rows)  
- Unit standardization, feature creation, anomaly detection  
- Cross-validating multiple public datasets  

**Statistical & Exploratory Analysis**  
- Time-series exploration  
- YoY volatility  
- Z-score outlier identification  
- Price-volume relationship analysis  

**Visualization & Communication**  
- Country-level comparative plots  
- Boxplots, line trends, and distribution charts  
- Professional documentation of data corrections & findings  

**Domain Expertise**  
- Coffee supply chains  
- Agricultural export economics  
- Market shocks (drought, rust outbreaks, price cycles)  
- Understanding of Arabica vs Robusta dynamics  

---

## 4. Why This Project

As a former **production & supply-chain manager in specialty coffee**, I wanted to build a data-driven lens on questions I’ve encountered in the industry:

- How do climate patterns influence coffee output?  
- How do global price cycles differ across producing regions?  
- Can we model risk, volatility, or yield changes over time?  

This project is the analytical foundation for a larger portfolio piece integrating **ERA5 climate data** to study rainfall, temperature, extreme events, and their lagged effects on production and pricing.

---

## 5. Next Steps

**Phase 2: Climate Integration**
- ERA5 rainfall & temperature processing  
- Seasonal climate variable engineering  
- Country-level climate–yield correlations  
- Lag analysis and predictive modeling  

**Phase 3: Modeling & Insights**
- Regression and time-series modeling  
- Country-specific climate sensitivities  
- Supply-chain risk implications  
- Visualization dashboard  

---

## 6. Repository Contents


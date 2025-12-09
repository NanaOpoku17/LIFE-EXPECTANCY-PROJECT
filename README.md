
# 📊 LIFE EXPECTANCY ANALYSIS PROJECT

A comprehensive Power BI data analysis project exploring the key drivers of global life expectancy across countries, regions, and income groups.

---

## 📌 Project Overview

This project analyzes a global life expectancy dataset to uncover patterns, determinants, and disparities across **174 countries**.  
Using **Power BI**, the analysis examines how economic development, health expenditure, sanitation levels, education spending, and disease burdens influence life expectancy outcomes.

---

## 🚀 Key Features of the Dashboard

### **1. Global Overview**
- **Average Life Expectancy:** 69.78 years  
- **Range:** 41 years (min) — 85 years (max)  
- **Avg. Health Expenditure:** 6.11%  
- **Avg. Education Expenditure:** 3.87%  
- **Avg. Corruption Index:** 2.60  

---

### **2. Country Performance Insights**
- **Highest Life Expectancy:** Japan (85 years)  
- **Lowest Life Expectancy:** Sierra Leone (41 years)

#### Visuals include:
- ✓ Health Expenditure Leaders  
- ✓ Education Spending Leaders  
- ✓ Undernourishment Hotspots  
- ✓ Unemployment & Injuries by Country  

---

### **3. Key Drivers of Life Expectancy**
- Strong positive correlation between **health spending** and life expectancy  
- **Access to sanitation** significantly increases longevity  
- **Undernourishment** reduces life expectancy  
- Disease burden varies by development level:  
  - **Communicable diseases** → more common in low-life-expectancy regions  
  - **Non-communicable diseases** → more common in high-life-expectancy nations  
- Clear income disparity:  
  - **High income:** 77.39 yrs  
  - **Low income:** 56.60 yrs  

---

## 🔧 Methods & Data Preparation

### **1. Data Cleaning**
- Removed outliers
- Corrected inconsistent text labels  
- Standardized **country and region** names  
- Handled missing values with domain-specific rules  

---

### **2. Data Type Adjustments**
- Converted numeric fields stored as text  
- Corrected date formats  
- Ensured whole number and decimal consistency  

---

### **3. Feature Engineering & DAX Measures**

#### KPI Measures Created:
- Average Life Expectancy  
- Average Health Expenditure  
- Average Education Expenditure  
- Minimum & Maximum Life Expectancy  
- Trend analysis measures  

#### Category Grouping (DAX):
```DAX
Life Exp Category =
IF([Life Expectancy] < 65, "Low",
    IF([Life Expectancy] < 75, "Medium", "High"))

---
#### 🛠️ Tools Used

- Power BI
- Microsoft Excel
- DAX (Data Analysis Expressions)
- Data Modelling Techniques

---

![WhatsApp Image 2025-12-08 at 17 04 41_29bd16bd](https://github.com/user-attachments/assets/81af07d9-7011-433d-8456-e54fa2452318)
![WhatsApp Image 2025-12-09 at 07 52 03_b9d3b503](https://github.com/user-attachments/assets/41f6c317-aee7-4c0e-b2ca-de96a94c388c)
![WhatsApp Image 2025-12-09 at 07 53 19_7c1df4e9](https://github.com/user-attachments/assets/d37b0506-a08c-42f4-b8ef-16d43d9bcee7)





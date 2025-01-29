# 📊 Sustainable Supply Chain Performance - Week 2 Report  

## **🚀 Project Overview**  
This project focuses on analyzing **sustainable supply chain performance** using Power BI.  
In **Week 2**, the following tasks were completed:  

✅ **Data Cleaning:** Rounding numeric values to enhance readability and consistency.  
✅ **Data Modeling:** Creating relationships between four key tables in Power BI.  

---

## **🛠️ Data Cleaning Steps**  
To ensure data quality, the following cleaning steps were performed:  

1️⃣ **Loaded the dataset** into Power BI.  
2️⃣ **Checked for missing values** (None found).  
3️⃣ **Rounded numeric values** to appropriate decimal places:  
   - Prices, Costs, and Revenue → Rounded to **2 decimal places**.  
   - Defect Rates → Rounded to **2 decimal place**.  
   - Stock Levels, Order Quantities → Rounded to **whole numbers**.  
4️⃣ **Ensured correct data types** (e.g., Text, Whole Number, Decimal).  

**Example of Rounding in Power Query:**
```DAX
Rounded Price = ROUND([Price], 2)
Rounded Costs = ROUND([Costs], 2)
Rounded Defect Rate = ROUND([Defect rates], 1)
```

---

## **Data Model (Screenshot)**
![Screenshot 2025-01-29 131332](https://github.com/user-attachments/assets/d2b730ff-4951-4338-bc34-aa3e89342983)

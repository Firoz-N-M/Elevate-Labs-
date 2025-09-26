# 📊 Zepto Data Analysis – SQL Project  

## 🔹 Project Overview  
This project focuses on **data exploration, cleaning, and analysis** of Zepto product data using SQL. The dataset contains information about product categories, prices, discounts, stock availability, and weights.  

---

## 🔹 Steps Performed  

### 1. Table Creation  
- Designed the `zepto` table with product attributes like `sku_id`, `category`, `name`, `mrp`, `discountPercent`, `availableQuantity`, `discountedSellingPrice`, `weightInGms`, `outOfStock`, and `quantity`.  

### 2. Data Exploration  
- Checked row count and displayed sample records.  
- Identified missing/null values.  
- Listed distinct product categories.  
- Compared in-stock vs out-of-stock products.  
- Found duplicate product names with multiple SKUs.  

### 3. Data Cleaning  
- Removed products with invalid prices (`mrp = 0 or discountedSellingPrice = 0`).  
- Converted price values from paise to rupees.  

### 4. Data Analysis  
- **Top 10 best-value products** based on discount percentage.  
- **High MRP but out-of-stock products** to identify demand gaps.  
- **Estimated revenue per category** using selling price × quantity.  
- **Products with MRP > 500 and discount < 10%**.  
- **Top 5 categories by average discount percentage**.  
- **Price per gram** for products above 100g to evaluate value-for-money.  
- **Weight categories (Low, Medium, Bulk)** for products based on weight.  
- **Total inventory weight per category** for stock management insights.  

---

## 🔹 Key Insights  
- Highlighted best deals for customers through discount analysis.  
- Identified expensive but low-discount items.  
- Measured potential revenue contribution by product categories.  
- Classified products based on weight to better understand inventory distribution.  


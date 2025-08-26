# ACME Company Analysis Project

## 👥 Group Members
- Komal Singh – ksingh0925@gmail.com  
- Julie Flament – juliemeflament@gmail.com  
- Vanshika Singla – vanshikasingla2002@gmail.com
  
---

## 📖 Executive Summary

ACME Company has not fully leveraged historical product sales data for strategic decision-making. This analysis aimed to extract insights from customer behavior, product sales, and inventory management to inform management decisions.

**Objectives:**  
- Establish a systematic analysis framework for customer behavior  
- Identify high-performing and underperforming products  
- Analyze pricing strategies and recommend adjustments  

**Value:**  
- Improve customer satisfaction and product distribution  
- Enhance revenue through data-driven decisions  
- Support company expansion with market insights  

**Conclusion:**  
Implementing analytics transforms ACME’s business strategy, enabling data-driven decisions that increase market share, customer satisfaction, and profitability.

---

## 📊 Summary Report

### Analysis: Customers by Region
- **Approach:** SQL queries to count customers per province; map and bar visualizations.  
- **Predictions:** Alberta increasing to ~89 customers by 2024; Quebec decreasing to 5.  
- **Recommendation:** Target marketing in high-growth provinces; strategic measures for declining regions.

### Analysis: Best and Worst Products
- **Top Products:**  
  | productName | totalRevenue |
  |------------|--------------|
  | Aerodynamic Copper Bag | 32,684.89 |
  | Heavy Duty Plastic Knife | 29,536.23 |
  | Ergonomic Iron Lamp | 25,879.65 |
  | Practical Cotton Wallet | 25,731.17 |
  | Incredible Wool Plate | 23,343.69 |

- **Worst Products:**  
  | productName | totalRevenue |
  |------------|--------------|
  | Sleek Bronze Keyboard | 2,404.30 |
  | Lightweight Aluminum Gloves | 3,502.07 |
  | Enormous Wool Wallet | 4,156.69 |
  | Synergistic Iron Car | 4,290.21 |
  | Fantastic Silk Knife | 4,515.65 |

- **Recommendation:** Increase promotion for top products; reduce focus on poorly performing items.

### Analysis: Payment Methods
- **Approach:** Counted usage in 2022; predicted 2024 usage via linear regression.  
- **Visualizations:** Distribution charts for 2022 and 2024 predictions.

### Analysis: Inventory Management
- **Approach:** Summed product inventory and values per warehouse; identified highest-selling products.  
- **Recommendation:** Optimize warehouse inventory for higher-value, high-selling products.

### Analysis: Your Choice #1 – Top Products by Category
- **Approach:** Analyzed sales and ratings by category.  
- **Recommendation:** Focus on appliances category; invest in top-rated and high-selling products.

### Database Improvements
- Optimize storage via normalization  
- Apply at least 3NF to reduce redundancy  
- Enhance security and prepare for growth  

### Suggested Tools
- Tableau recommended for multi-table analysis, visualizations, and collaboration  

---

## 🌐 Sources / References
- [Asana Executive Summary Examples](https://asana.com/resources/executive-summary-examples)  
- [ChatGPT](https://chat.openai.com/c/8985619a-56dd-4dd3-9498-8060e9f998e6)  
- [Microsoft Map Charts](https://support.microsoft.com/en-us/office/create-a-map-chart-in-excel-f2cfed55-d622-42cd-8ec9-ec8a358b593b)  
- [Microsoft Forecast Functions](https://support.microsoft.com/en-us/office/forecast-and-forecast-linear-functions-50ca49c9-7b40-4892-94e4-7ad38bbeda99)  
- [Sales Layer – Database Normalization](https://blog.saleslayer.com/why-is-database-normalization-so-important)

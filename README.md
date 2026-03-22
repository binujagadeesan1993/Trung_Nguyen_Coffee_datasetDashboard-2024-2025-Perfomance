
# ☕ Trung Nguyen Coffee Export Performance Dashboard (2024–2025)

## 📊 Project Overview
This project presents a comprehensive analysis of **Trung Nguyen Coffee’s export performance** for the fiscal period **2024–2025** using **Power BI**.

The dashboard evaluates:
- Key Performance Indicators (KPIs)
- Product-level revenue distribution
- Category-wise margin analysis
- Country-level export performance
- Quarterly revenue & profit trends
- Interactive slicer-based filtering

---

## 📁 Dataset Information
- Source: Internal sales/export dataset
- Duration: 5 years dataset (Filtered to 2024–2025)
- Tool Used: Microsoft Excel + Power BI

### 🧮 Calculated Column
```excel
Revenue_Margin = IF(K2>=1000,"Good",
                   IF(K2>=600,"Average",
                   IF(K2>=400,"Moderate","Need Review")))

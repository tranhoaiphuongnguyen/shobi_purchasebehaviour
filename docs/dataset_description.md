## Dataset description

**Period covered:** 21 January 2023 – 21 July 2024  
**Scope:** 10,745 transactions (online orders)  
**Granularity:** Customer–Order level  

**Key variables**
- Customer demographics: `Gender`, `Size`, `Location` (State)  
- Purchase details: `Date`, `Season`, `Category`, `Color`, `Purchase Amount`, `Review Rating`  
- Behavioral attributes: `Previous Purchases`, `Frequency` (Weekly/Monthly/Quarterly)  
- Payment & Logistics: `Method`, `Shipping Type`, `Discount`, `Promo Code`  

**Data preparation**
- Removed duplicates (–2.3% of rows) and standardised category values.  
- Checked missing values in `Sales Amount` and `Review Rating` — <0.5% missing, replaced with category mean.  
- Converted dataset to an Excel Table for dynamic range linking with PivotTables.
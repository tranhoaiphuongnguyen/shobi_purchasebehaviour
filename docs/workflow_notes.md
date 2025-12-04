## Methodology

**Analytical workflow**

The entire dashboard was built using PivotTables as the analytical backbone.  
Each PivotTable summarises sales data by different business dimensions (Category, Season, Location, Payment Method, etc.) and automatically performs calculations such as totals, averages, and counts.

All metrics and charts are connected through Excel Slicers, when a slicer is applied, all PivotTables and KPI cards update instantly.

**KPI metrics**

The key performance indicators (KPIs) displayed at the top of the dashboard were generated directly from PivotTables.  
Each value is a live cell reference linked to a PivotTable output.

| KPI | Calculation method | Description |
|------|--------------------|-------------|
| Total Revenue | PivotTable aggregation (`Sum of Sales Amount`) | Measures overall sales across all transactions |
| Average Rating | PivotTable aggregation (`Average of Review Rating`) | Reflects customer satisfaction level |
| Customer Count | PivotTable aggregation (`Count of Customer ID`) | Shows the number of active customers |
| Previous Purchases | PivotTable aggregation (`Count of Previous Purchases > 0`) | Indicates repeat customer activity |

**Dashboard components**

- PivotTables: Revenue by Category, Season, Payment Method, Location, Color, and Frequency  
- Charts: Column, Pie, Combo, Map, and Radar (linked to PivotTable ranges)  
- Slicers: Category, Season, Location, Gender, Size, Color  
- Layout: KPI cards on top, charts in grid layout for comparison and storytelling  
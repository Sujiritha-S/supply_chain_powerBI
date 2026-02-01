# Supply Chain Performance Analysis — Power BI Report  

An interactive Power BI report analyzing shipment efficiency, supplier quality, product movement, and operational costs across the supply chain using DAX and a structured data model.

## Dashboard Preview  
<img width="1361" height="763" alt="dashboard_preview1" src="https://github.com/user-attachments/assets/e24cdaee-5e1c-4357-926e-32111737fd74" />
<img width="1353" height="772" alt="dashboard_preview2" src="https://github.com/user-attachments/assets/457289ef-dbac-4223-a2b2-ad61d6119da1" />
<img width="1358" height="759" alt="dashboard_preview3" src="https://github.com/user-attachments/assets/cd37422b-2091-4d91-bfe5-2eabd5a73ba0" />
<img width="1352" height="763" alt="dashboard_preview4" src="https://github.com/user-attachments/assets/bfdbfa57-b6b3-421b-9ca7-fc9706d39a66" />
<img width="1358" height="759" alt="dashboard_preview5" src="https://github.com/user-attachments/assets/64d1e675-21cd-4be6-abe9-a717b01a20f4" />

## Files Included  
- `Supply_Chain_Analysis.pbix`  
- supply_chain_data – Data Source   

## Features / Highlights  

### KPI Summary  
- Total Revenue Generated  
- Total Products Sold  
- Total Shipping Cost  
- Average Shipping Time  
- Average Lead Time  
- Average Defect Rate  

### Carrier Performance Analysis  
- Shipping cost by carrier and transportation mode  
- Average shipping time by carrier  
- Comparison of delivery efficiency across logistics partners  

### Supplier & Quality Analysis  
- Average defect rate by supplier  
- Supplier lead time vs manufacturing lead time  
- Inspection result distribution (Pass / Fail / Pending)  

### Product Shipment Analysis  
- Revenue by product type  
- Shipping cost by product type  
- Products sold by location  
- Demand and cost patterns across product categories  

### Product Details (Drill-through)  
- SKU-level operational metrics  
- Revenue, order quantity, stock levels, availability, and operational cost  
- Top SKUs by revenue with product type comparison  

## Tools & Techniques  
- Power BI Desktop  
- Power Query Editor  
- DAX (for KPIs, averages, ratios, and aggregations)  
- Interactive slicers and drill-through navigation  
- Consistent dashboard layout and visual formatting  

## Data Preparation  

**Steps performed in Power Query:**  
- Removed irrelevant columns  
- Renamed columns for clarity and consistency  
- Corrected data types  
- Handled missing and inconsistent values  
- Prepared fields for KPI calculations and drill-through analysis
- Cost-related fields were scaled for reporting consistency to improve interpretability of operational cost metrics.

## DAX Measures & Functions  

Custom calculations were created using key DAX functions and calculated columns:  

| Function | Purpose |
|--------|---------|
| `SUM()` | Total revenue, shipping cost, order quantities |
| `AVERAGE()` | Average shipping time, lead time, stock levels |
| `COUNT()` | Count of orders or products |
| `FORMAT()` | Month name formatting for visuals |
| `MONTH()` | Extracted month from date fields |

## Future Enhancements  
- Trend analysis for defects and lead times  
- Inventory turnover and stock-out risk indicators  
- Profitability analysis (Revenue vs Operational Cost)  
- Additional drill-through pages for supplier and carrier details  

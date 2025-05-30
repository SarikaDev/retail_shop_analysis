#  Retail Analytics Performance Suite (2019-2024)

## Executive Summary
This end-to-end retail analytics solution transforms 6 years of transactional data into actionable business intelligence. Designed as a portfolio showcase, this project demonstrates advanced Power BI capabilities with custom Figma-designed UX components across five interconnected dashboards.

## Project Highlights
✅ **5 Comprehensive Dashboards**: Sales, Inventory, Returns, Products, and Customer analytics  
✅ **Customer-Centric Design**: Behavioral insights across 5 key customer segments  
✅ **Custom UI/UX**: Figma-designed visualization components  
✅ **Technical Sophistication**: DAX measures, time intelligence, and drill-through capabilities  

## Dashboard Portfolio

### 1. Sales Performance 
[![Sales Dashboard](./assets/Sales_dashboard.png)](./assets/Sales_dashboard.png "View image (right-click to save)")

- Annual revenue trends with YoY growth analysis
- Seasonality patterns and promotional impact
- Sales channel performance (in-store vs online)

### 2. Employee and Supplier 
[![Inventory Dashboard](./assets/Supplier_dashboard.png)](./assets/Supplier_dashboard.png "View image (right-click to save)")

- Stock turnover rates by product category
- Inventory aging analysis
- Replenishment recommendations

### 3. Returns and Refund Overview
[![Returns Dashboard](./assets/Return_dashboard.png)](./assets/Return_dashboard.png "View image (right-click to save)")

- Return rate trends by product/customer
- Return reason analysis
- Financial impact assessment

### 4. Product and Inventory Overview
[![Product Dashboard](./assets/Product_dashboard.png)](./assets/Product_dashboard.png "View image (right-click to save)")

- Product category profitability
- Price elasticity insights
- Cross-selling opportunities

### 5. Customer 360° Dashboard
[![Customer Dashboard](./assets/Customer_dashboard.png)](./assets/Customer_dashboard.png "View image (right-click to save)")

- Customer lifetime value analysis
- Purchase frequency trends
- RFM segmentation


## 💡 Why This Stands Out

**"Most retail dashboards show what happened - this system reveals why and what to do next"**

▸ **Time-Travel Analytics**: Slide through 72 months with seamless period comparisons  
▸ **Customer DNA Profiles**: Behavioral fingerprints for all 5 key accounts  
▸ **Predictive Signals**: Built-in alerts for stockouts/overstocks before they happen  
▸ **Decision Flow**: Each dashboard guides users to next-best-action  

## Technical Implementation

## Tech Stack  

![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi)  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17+-blue?logo=postgresql)  
![Figma](https://img.shields.io/badge/Figma-Design_Prototypes-purple?logo=figma)  


### Data Architecture
```mermaid
graph TD
    A[Figma Design]
    A1[Raw CSV Data] --> B[PostgreSQL-connected via power BI]
    B --> C[Data Model]
    C --> D[DAX Measures]
    D --> E[Interactive Visuals]

    
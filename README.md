# Sales Performance Dashboard — Power BI

An end-to-end Power BI dashboard analyzing **1,000 sales transactions** across 4 regions, 5 sales reps, and 4 product categories.

## Preview
![Dashboard Preview](dashboard.png)

## Key Insights
- Total revenue: **$5,019,265** across all regions and categories
- Clothing leads in sales at **$1.31M**, followed closely by Furniture and Electronics
- The **North region** generated the highest revenue at $1.37M
- **David** ranked #1 sales rep with $1.14M in total sales
- Retail and Online channels are nearly equal: **51% vs 49%**
- New vs Returning customer revenue split is almost even — indicating strong retention
- Average discount applied across transactions: **15.2%**

## Dashboard Visuals
| Visual | Purpose |
|---|---|
| Bar chart | Sales by product category |
| Map / region breakdown | Revenue by region |
| Sales rep leaderboard | Performance ranking |
| Channel comparison | Online vs Retail split |
| Customer type donut | New vs Returning revenue |
| Payment method chart | Cash / Credit Card / Bank Transfer |
| KPI cards | Total revenue, qty sold, avg discount |

## Tools Used
- **Power BI Desktop** — data modeling, DAX measures & visualizations
- **Microsoft Excel** — data cleaning & preparation

## Files
| File | Description |
|---|---|
| `Icareer.pbix` | Power BI project file |
| `sales_data.xlsx` | Cleaned sales dataset (1,000 rows) |
| `dashboard.png` | Dashboard screenshot |

## Dataset Overview
| Column | Description |
|---|---|
| Product_ID | Unique product identifier |
| Sale_Date | Date of transaction |
| Sales_Rep | Name of sales representative |
| Region | North / South / East / West |
| Sales_Amount | Revenue from the transaction |
| Quantity_Sold | Units sold |
| Product_Category | Furniture, Electronics, Clothing, Food |
| Unit_Cost / Unit_Price | Cost and price per unit |
| Customer_Type | New or Returning |
| Discount | Discount rate applied |
| Payment_Method | Cash, Credit Card, Bank Transfer |
| Sales_Channel | Online or Retail |

## Color Theme
Custom palette for visual consistency:
- Navy `#1A2F4B` · Steel Blue `#2E86AB` · Teal `#1D9E75`
- Amber `#EF9F27` · Coral `#D85A30` · Violet `#6C63FF`

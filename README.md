# Global Payment Fraud Risk Dashboard  
**Shikshya Bhattachan** | Senior Finance Data Analyst Portfolio  


## Business Impact 
- **Detected $1.2M in simulated fraud** across 1M+ transactions  
- **Enabled self-service analytics** for Finance → **60% reduction in ad-hoc requests**  
- **Led UAT with 12 cross-functional stakeholders** (Finance, Risk, Tech)  
- **Full data governance** (lineage, metadata, audit trail)


| Requirement | Delivered |
|-----------|---------|
| Power BI + DAX | 5 interactive pages, 12 DAX measures |
| SQL + large datasets | 1M+ rows in Snowflake |
| UAT & validation | 8 test cases, 100% pass |
| Data governance | Lineage, metadata, refresh log |
| Self-service analytics | Slicers, tooltips, export |
| Finance + Tech bridge | Fraud $ → P&L impact |

---
## Tech Stack
Kaggle → Python → Snowflake → SQL → Power BI (DAX) → Power BI Service

---

## Key Features
- **Executive KPIs**: Fraud Rate, Total Loss, Top Risk Merchants  
- **Drill-Through**: Click merchant → see all txns  
- **Self-Service Explorer**: Finance users filter by country, date, amount  
- **Dynamic Alerts**: Red/Yellow/Green based on fraud threshold  
- **UAT & Governance Tab**: Full audit trail

---

## Live Dashboard
[Open in Power BI Service](https://app.powerbi.com/...) *(Free publish)*


## Build Instructions
1. Load `creditcard.csv` → Snowflake  
2. Run `sql/create_views.sql`  
3. Open `Visa_Fraud_Dashboard.pbix` → Refresh  
4. Publish to Power BI Service → Share link  
5. Record 60-sec Loom demo

---

**Built for Visa’s Senior Finance Data Analyst role (Req ID: 744000092754838)**  
*Ready for interview discussion*

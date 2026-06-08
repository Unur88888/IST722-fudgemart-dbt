# IST722-fudgemart-dbt

# IST722 – Fudgemart, Inc. Data Warehouse (Snowflake + dbt)

This project integrates two fictional companies—Fudgemart (retail) and Fudgeflix (streaming)—into a unified Snowflake data warehouse. Using dbt, I built modular ELT pipelines to transform raw source tables into a dimensional model supporting combined sales and subscription analytics.

## Files in this Repository
- `FinalProject.sql` — SQL transformations and validation queries  
- `Group3_Dimensional_Modeling.pdf` — star schema and dimensional model design  
- `Group 3 Final Project.pptx` — presentation summarizing the warehouse build  
- `Group3_FudgeMart Inc Sales.pbix` — Power BI dashboard  
- Additional dbt model files and supporting documentation

## Tools & Technologies
Snowflake, dbt, SQL, Power BI

## Key Findings
- Successfully unified Fudgemart and Fudgeflix data into a shared star schema.  
- Built a `fact_sales` table combining 3,516 Fudgemart orders, 10,466 order line items, and 1,294 Fudgeflix billing records.  
- dbt enabled modular, testable transformations and lineage tracking.  
- Power BI visualized unified sales, category performance, and time‑based trends.

## Author
Unur Gantulga  
MS in Applied Data Science, Syracuse University

# Data-to-Dashboards-360-Source-System-S3-Snowflake-Power-BI
Raw Data to Data driven analysis - Snowflake retail warehouse

Architected a retail analytics data warehouse using ER modeling and dimensional design (star/snowflake): central FactOrders with conformed Date, Customer, Product, Store, Loyalty dimensions, surrogate keys, constraints, and analytics-ready grain for time/region/product drill-downs.

Engineered realistic synthetic datasets with Python (Pandas, NumPy, Faker, CSV) and Excel lookups: full DimDate (2015–2025), customers/products/stores, and per-store daily order files for 100 stores (≈10k–100k rows/day), including data cleansing and deterministic IDs for reliable joins.

Operationalized ingestion on Snowflake: created DB/schema/tables, reusable FILE FORMATs and STAGEs; bulk loaded via SnowSQL + COPY INTO; integrated AWS S3 with STORAGE INTEGRATION (IAM) and event-driven Snowpipe for continuous ELT; monitored with PIPE STATUS and COPY_HISTORY.

Delivered analytics & BI: scenario-based SQL (CTEs, aggregations) for KPIs (Revenue, AOV, Discount/Shipping impact, YoY); built interactive Power BI dashboards with drill-downs by region/store/product—accelerating time-to-insight and setting the stage for agentic-AI assisted data generation and query authoring.

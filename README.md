# Spyros Papastergiou

Financial Data Analyst. Business Intelligence. FinTech.

Live portfolio: https://phytai.com
Email: papastergiousp@gmail.com
Tableau Public: https://public.tableau.com/app/profile/spyros.papastergiou

## About

Financial Data Analyst with hands-on experience in Python, SQL, Power BI, and Tableau. I build end-to-end pipelines from raw data extraction to KPI dashboards, with a focus on banking, retail, and operations. Open to work.

## Tech stack

Python, SQL, SQLite, Power BI, DAX, Tableau, pandas, NumPy, Matplotlib, Plotly, Seaborn, ETL, Advanced Excel, Jupyter.

## Featured projects

Each project below uses the STAR framework (Situation, Task, Action, Result) so you can quickly see what was done and why it mattered.

### 1. Greek Banking Sector Analysis 2022 to 2024

Repo: https://github.com/papastergiousp-maker/Greek-Banking-Financial-Analysis
Live dashboard: https://phytai.com/dashboard

Situation. The four Greek systemic banks (Eurobank, Alpha Bank, Piraeus Bank, NBG) emerged from a decade of recapitalization. Rising interest rates from 2022 onwards opened a window to grow Net Interest Income, but each bank's efficiency, capital strength, and lending discipline diverged. No single comparable view existed.

Task. Build one comparable view of all four banks across profitability, efficiency, lending, and balance sheet strength for 2022 to 2024.

Action. Extracted financials from twelve official Annual Report PDFs using pdfplumber. Cleaned and reconciled across different reporting formats. Loaded into a SQLite database. Computed standardized KPIs: ROE, Cost-to-Income, Loan-to-Deposit, NIM, year-over-year growth. Built an interactive dashboard with sql.js running in the browser and Plotly charts. No backend, fully static.

Result. Eurobank NII grew 72 percent in two years, Cost-to-Income improved from 46.8 to 33.0. NBG showed the strongest NIM expansion (1.75 to 3.14). Piraeus operated with the lowest Cost-to-Income at 31.8 percent. Alpha trailed in profitability with ROE between 5.5 and 8.2 percent. Deployed live at phytai.com/dashboard.

### 2. Eurobank Financial Analysis 2022 to 2024

Stack: Python, SQL, SQLite, Power BI, DAX
Repo: https://github.com/papastergiousp-maker/ETL_Pipelines

Situation. Eurobank reported strong topline growth post-rate hikes, but the underlying drivers were not visible in any single artifact.

Task. Build a Power BI dashboard from official Annual Report PDFs that shows three-year evolution of key banking KPIs.

Action. Pipeline: PDF extraction with pdfplumber, cleaning with pandas, persistence in SQLite, KPI queries with SQL window functions and JOINs, dashboard with custom DAX measures.

Result. NII grew 72 percent over two years. Cost-to-Income improved from 46.8 to 33.0. ROE 16.9 percent, above the European banking average of around 12 percent. Loan-to-Deposit 68.3 percent. Net Profit up 27 percent year-over-year in 2024.

### 3. Supermarket Sales and KPI Dashboard

Stack: Power BI, DAX
Repo: https://github.com/papastergiousp-maker/Power-BI

Situation. Multi-branch supermarket operation needed to identify which product lines and customer segments drive revenue and gross income.

Task. Build an executive dashboard with dynamic slicers for branch, gender, and product line.

Action. Designed KPI cards, breakdown charts, and dynamic slicers in Power BI with custom DAX measures.

Result. 41.77 million dollars total revenue across 1,000 orders. Health and Beauty led gross income at 7.9 million dollars. Fashion Accessories drove 17.8 percent of total order volume. Female customers generated higher average basket value across all branches.

### 4. Operational KPI and Quality Control Dashboard

Stack: Power BI, DAX
Repo: https://github.com/papastergiousp-maker/Power-BI

Situation. Multi-location operation showed inconsistent quality scores, but the cost of defects and fatal errors was not quantified.

Task. Surface performance gaps between supervisors and locations, and quantify the financial impact of defects.

Action. Built a management dashboard with supervisor-level breakdowns, defect rate calculations, and quality score trends.

Result. 131K total tasks monitored. Defect rate 20 percent, fatal error rate 8 percent. Quality score 71.75 out of 100, below the 80 percent industry benchmark. Clear performance gaps surfaced between supervisors and locations.

### 5. Sales Profitability and Shipping Analysis

Stack: Tableau
Live: https://public.tableau.com/app/profile/spyros.papastergiou

Situation. Multi-region retail with mixed shipping methods and product categories. Margin erosion was suspected but not localized.

Task. Find which regions, shipping methods, and categories generate the highest profit margins.

Action. Built a Tableau dashboard with regional, shipping, and category breakdowns over a three-year window.

Result. Standard Class carried 57.3 percent of orders generating 164 thousand dollars in revenue. Philadelphia and New York were top revenue cities. Technology had the highest profit margin per category, Furniture the lowest. West region outperformed all others in total sales volume.

### 6. Industrial Quality Control and Financial Risk Modeling

Stack: Python, pandas, NumPy
Repo: https://github.com/papastergiousp-maker/Industrial-Quality-Control-Financial-Risk-Modeling

Situation. Production batch failures were monitored qualitatively but not connected to financial impact. Synthetic data scenario for methodology demonstration.

Task. Quantify the cost of correctable versus critical batch failures using a process-driven simulation.

Action. Simulated 480 production batches using a Normal Distribution against business-defined pH thresholds. Built classification logic to distinguish correctable versus critical failure batches. Assigned cost weights to each outcome.

Result. Total simulated financial impact 76 thousand euros: 56 thousand in correction costs, 20 thousand in critical waste. Output is a financial cost summary, not just visualization.

### 7. ETL Pipelines

Stack: Python, SQL, SQLite, Power BI
Repo: https://github.com/papastergiousp-maker/ETL_Pipelines

Situation. Real-world business data lives in PDFs, APIs, and Excel files. Most analytics work assumes clean data and ignores the extraction reality.

Task. Demonstrate end-to-end pipelines on real datasets, from raw extraction to production dashboards.

Action. Built pipelines covering PDF extraction, cleaning, SQL database design, KPI analysis, and dashboard rendering.

Result. Reproducible pipelines published with all steps documented and runnable.

### 8. Business Analytics Live Dashboard

Stack: Python, Plotly
Live: https://phytai.com/dashboard
Repo: https://github.com/papastergiousp-maker/PhytAI-Deployment

Situation. Power BI and Tableau require licenses or are tied to vendor platforms. A pure-Python alternative for live business dashboards was worth proving out.

Task. Build and deploy an interactive analytics dashboard entirely in Python, with no BI tool.

Action. Built the dashboard with Plotly, deployed it as a static site on a custom domain. Backend logic published on GitHub.

Result. Live at phytai.com/dashboard. End-to-end deployment from data to production web interface.

## Repositories

| Repo | What it contains |
|------|------------------|
| [Greek-Banking-Financial-Analysis](https://github.com/papastergiousp-maker/Greek-Banking-Financial-Analysis) | Comparative analysis of Eurobank, Alpha, Piraeus, NBG for 2022 to 2024. Live at phytai.com/dashboard. |
| [ETL_Pipelines](https://github.com/papastergiousp-maker/ETL_Pipelines) | End-to-end pipelines: PDF, API, cleaning, SQL, Power BI. |
| [Power-BI](https://github.com/papastergiousp-maker/Power-BI) | Seven .pbix files plus screenshots: Eurobank, Supermarket, Operational KPI, Super Store, Hospital, COVID-19, DAX assignment. |
| [Python_Financial_Data_Analytics](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics) | Top 15 Python-for-finance projects. |
| [Industrial-Quality-Control-Financial-Risk-Modeling](https://github.com/papastergiousp-maker/Industrial-Quality-Control-Financial-Risk-Modeling) | Process-driven financial risk simulation. |
| [PhytAI-Deployment](https://github.com/papastergiousp-maker/PhytAI-Deployment) | Source code for phytai.com, including the live Plotly dashboard. |

## Data sources

Data is sourced from official sources (Annual Reports, public datasets, Kaggle). All financial figures are in millions unless stated otherwise.


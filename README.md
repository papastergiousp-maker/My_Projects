# Spyros Papastergiou — Data & BI Analyst

**Financial Data Analysis · Business Intelligence · FinTech**

🌐 [phytai.com](https://phytai.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://linkedin.com/in/spyros-papastergiou) &nbsp;·&nbsp; 📊 [Tableau Public](https://public.tableau.com/app/profile/spyros.papastergiou/vizzes) &nbsp;·&nbsp; 🟢 **Open to Work**

> Financial Data Analyst with hands-on experience in Python, SQL, Power BI, and Tableau. Focused on end-to-end pipelines — from raw data extraction to actionable KPI dashboards. 26+ projects across banking, retail, quality control, and FinTech.

---

## Tech Stack

`Python` `SQL` `SQLite` `Power BI` `DAX` `Tableau` `pandas` `NumPy` `Matplotlib` `Plotly` `Seaborn` `ETL` `Advanced Excel` `Jupyter`

---

## 🏆 Top 8 Projects

---

### 🏦 1 · Eurobank Financial Analysis 2022–2024
**Python · SQL · SQLite · Power BI · DAX**

**Business question:** How did Eurobank's financial performance evolve from 2022 to 2024, and what KPIs signal its position relative to the European banking average?

**Pipeline:** PDF extraction (pdfplumber) → data cleaning (pandas) → SQLite database → SQL KPI queries (Window Functions, JOINs) → Power BI dashboard with custom DAX measures

| KPI | 2022 | 2023 | 2024 |
|:----|:-----|:-----|:-----|
| Net Interest Income | €1,456m | €2,174m | €2,504m |
| Cost-to-Income | 46.8% | 38.2% | 33.0% |
| Loan-to-Deposit | 75.2% | 72.4% | 68.3% |
| Net Profit | €1,353m | €1,148m | €1,458m |
| ROE | — | — | 16.9% |

**Key insights:**
- NII grew +72% over 2 years — driven by rising interest rates and strong loan book growth
- Cost-to-Income improved from 46.8% → 33.0% — significant operational efficiency gains
- ROE at 16.9% — above the European banking average (~12%)
- Loan-to-Deposit at 68.3% — healthy liquidity, well below the 80% risk threshold
- Net Profit +27% YoY in 2024 despite a challenging macro environment

**No pre-cleaned datasets used — all data extracted directly from official Eurobank Annual Report PDFs.**

→ [📂 View Repo](https://github.com/papastergiousp-maker/ETL_Pipelines/tree/main/eurobank-financial-analysis)

---

### 🛒 2 · Supermarket Sales & KPI Dashboard
**Power BI · DAX**

**Business question:** Which product lines and customer segments drive the most revenue and gross income in a multi-branch supermarket operation?

**Key insights:**
- $41.77M total revenue across 1,000 orders
- Health & Beauty led gross income at $7.9M — highest margin category
- Fashion Accessories drove the highest order volume at 17.8% of total orders
- Female customers generated higher average basket value across all branches
- Dynamic slicers allow filtering by branch, gender, and product line for operational decisions

→ [📊 View Dashboard](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/Supermarket%20Sales%20%26%20KPI%20Dashboard.pdf) &nbsp;·&nbsp; [⬇ Download .pbix](https://github.com/papastergiousp-maker/Power-BI/tree/main/Power_BI_Projects)

---

### ⚙️ 3 · Operational KPI & Quality Control Dashboard
**Power BI · DAX**

**Business question:** Where are the performance gaps in a multi-location operation, and what is the financial cost of defects and fatal errors?

**Key insights:**
- 131K total tasks monitored across all locations
- Overall defect rate: 20% — fatal error rate: 8%
- Overall quality score: 71.75/100 — below the 80% industry benchmark
- Supervisor-level breakdown exposed clear performance gaps between locations
- Dashboard designed for management-level decision-making — not just reporting

→ [📊 View Dashboard](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/Operational%20KPI%20%26%20Quality%20Control%20Dashboard.pdf) &nbsp;·&nbsp; [⬇ Download .pbix](https://github.com/papastergiousp-maker/Power-BI/tree/main/Power_BI_Projects)

---

### 📈 4 · Sales Profitability & Shipping Analysis
**Tableau**

**Business question:** Which regions, shipping methods, and product categories generate the highest profit margins — and where are costs eroding returns?

**Key insights:**
- Standard Class carried 57.3% of all orders ($164K revenue) — most cost-efficient shipping mode
- Philadelphia and New York City were the top revenue cities
- Technology had the highest profit margin per category; Furniture showed the lowest
- Sales grew steadily from 2016 to 2019 — upward trend consistent across all regions
- West region outperformed all others in total sales volume

→ [📊 View on Tableau Public](https://public.tableau.com/app/profile/spyros.papastergiou/viz/TableauFinalAssigment_17639274180640/Dashboard1)

---

### 💳 5 · Credit Card Spending Analytics — India
**Tableau**

**Business question:** How do spending patterns differ across card types, categories, and gender segments in India's top urban markets?

**Key insights:**
- Food, Entertainment, and Grocery were the top 3 spending categories across all cities
- Silver and Platinum cardholders showed distinctly different category preferences
- Male and female cardholders diverged most significantly in Travel and Bills categories
- Mumbai and Delhi accounted for the majority of total tracked expenditure
- City-wise breakdown reveals concentration of high-value transactions in 2 of 5 cities

→ [📊 View on Tableau Public](https://public.tableau.com/app/profile/spyros.papastergiou/viz/CreditCardHabitsinindia/Dashboard1)

---

### 🛢️ 6 · Retail Finance Sales Analysis
**Python · pandas · NumPy · Matplotlib · Plotly · Seaborn**

**Business question:** Which stores, products, and geographic zones drive the most liquor sales volume — and how is market share distributed?

**Key insights:**
- End-to-end ETL pipeline on a real Iowa liquor sales dataset (2016–2019)
- Top 15 stores captured the majority of total sales volume — high concentration of revenue
- Geographic zip code analysis revealed 3 key high-demand distribution zones
- Market share analysis showed that the top 5 vendors control >60% of category revenue
- Store-level percentage share visualisation enables targeted distribution strategy

→ [📂 View Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Retail_Analysis/FINANCE_LIQUOR_SALES.ipynb)

---

### 🧪 7 · Production Quality & Financial Impact Analysis
**Python · pandas · NumPy · Matplotlib · Seaborn**

**Business question:** What is the direct financial cost of production batch failures — and how can pH thresholds be used to predict and prevent losses?

**Key insights:**
- Simulated 480 production batches using Normal Distribution with business-defined pH thresholds
- Total financial impact: €76K across all batches
- €56K attributed to correction costs, €20K to critical waste (unsalvageable batches)
- Classification model distinguished "correctable" vs "critical failure" batches with financial output
- Built as a financial reporting tool — output is a cost summary, not just a visualisation

→ [📂 View Repo](https://github.com/papastergiousp-maker/Industrial-Quality-Control-Financial-Risk-Modeling/blob/main/INDUSTRIAL%20ANOMALY%20DETECTION.ipynb)

---

### 🌐 8 · Business Analytics Live Dashboard
**Python · Plotly**

**Business question:** Can a fully interactive business analytics dashboard be built and deployed in Python — without any BI tool?

**Key insights:**
- Real-time interactive dashboard built entirely in Python with Plotly — no Power BI, no Tableau
- Deployed live at [phytai.com/dashboard](https://phytai.com/dashboard)
- Demonstrates end-to-end deployment capability from data to production web interface
- Backend logic published on GitHub for full transparency

→ [🌐 Live Demo](https://phytai.com/dashboard) &nbsp;·&nbsp; [📂 View Repo](https://github.com/papastergiousp-maker/My_Projects/blob/main/Business%20Dashboard.ipynb)

---

## 📊 All Power BI Projects

Screenshots available to view directly. `.pbix` files available to download and open interactively in Power BI Desktop.

| Project | Key Insight | Screenshot | .pbix |
|:--------|:------------|:-----------|:------|
| Supermarket Sales & KPI Dashboard | $41.77M revenue · Health & Beauty top margin | [View](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/Supermarket%20Sales%20%26%20KPI%20Dashboard.pdf) | [Download](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Projects/Supermarket%20Sales%20%26%20KPI%20Dashboard.pbix) |
| Operational KPI & Quality Control | 131K tasks · 20% defect rate · score 71.75/100 | [View](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/Operational%20KPI%20%26%20Quality%20Control%20Dashboard.pdf) | [Download](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Projects/Operational%20KPI%20%26%20Quality%20Control%20Dashboard.pbix) |
| Global COVID-19 Analytics Dashboard | Confirmed cases trend & country-level spread | [View](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/Global%20COVID-19%20Analytics%20Dashboard.pdf) | [Download](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Projects/Global%20COVID-19%20Analytics%20Dashboard.pbix) |
| Retail Sales Analytics Dashboard | Regional performance & product category breakdown | [View](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/Retail%20Sales%20Analytics%20Dashboard.pdf) | [Download](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Projects/Retail%20Sales%20Analytics%20Dashboard.pbix) |
| COVID-19 Global Spread & Recovery | Recovery rate trends vs active cases over time | [View](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/COVID-19%20Global%20Spread%20%26%20Recovery%20Analysis.pdf) | [Download](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Projects/COVID-19%20Global%20Spread%20%26%20Recovery%20Analysis.pbix) |
| DAX Assignment | Custom DAX measures · calculated columns · KPI logic | [View](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Screenshots/DAX-Assigment.pdf) | [Download](https://github.com/papastergiousp-maker/Power-BI/blob/main/Power_BI_Projects/DAX-Asigment.pbix) |

---

## 📈 All Tableau Projects

→ [View all on Tableau Public](https://public.tableau.com/app/profile/spyros.papastergiou/vizzes)

| Project | Key Insight | Link |
|:--------|:------------|:-----|
| Sales Profitability & Shipping | Standard Class = 57.3% of orders · West region leads | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/TableauFinalAssigment_17639274180640/Dashboard1) |
| Credit Card Spending — India | Food & Entertainment top spend · Mumbai & Delhi dominate | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/CreditCardHabitsinindia/Dashboard1) |
| Top Tech Companies — Stock & Market Cap | PE ratio vs market cap comparison across FAANG+  | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/TopTechCompanies_17639834270630/Dashboard1) |
| Supermarket Sales Dashboard | Profit trend & category performance over time | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/supermarketsales_17634106686220/Dashboard1) |
| Sales, Profit & Shipping Performance | Regional margins & shipping cost impact | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/CaseStudy4_17636468194810/Dashboard1) |
| COVID-19 Global Trends | Confirmed cases by country · spread timeline | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/CaseStudy3_17636451961470/Dashboard1) |
| Sales & Orders Performance | Order volume trends · regional KPI breakdown | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/Casestudy2_17636423216710/Dashboard1) |
| Financial Performance Pivot | Multi-dimensional financial data exploration | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/Data-Pivot/Sheet1) |
| Business Performance Story | Forecasting & executive narrative dashboard | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/Book3_17632367210010/Story2) |
| Retail & Consumer Data Analysis | Foundational sales segmentation & visualisation | [View](https://public.tableau.com/app/profile/spyros.papastergiou/viz/CaseStudy1__17635864847270/Dashboard1) |

---

## 🐍 All Python Projects

| # | Project | Business Question | Key Insight | Link |
|:--|:--------|:------------------|:------------|:-----|
| 1 | Retail Finance Sales Analysis | Which stores & zones drive volume? | Top 15 stores = majority of sales · 3 key zip zones | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Retail_Analysis/FINANCE_LIQUOR_SALES.ipynb) |
| 2 | Betting Risk Analysis | How do odds & probability affect risk exposure? | Risk quantification model with expected value & variance | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Betting_Risk_Analysis/Betting_Risk_Analysis.ipynb) |
| 3 | E-Commerce Sales | What drives sales performance in e-commerce? | Seasonal trends & category performance analysis | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/E-Comerce_Sales/%CE%95-COMERCE_Sales.ipynb) |
| 4 | Stock Market Analysis (MSFT) | How has Microsoft stock performed over time? | Price trend, moving averages & volatility analysis | [Repo](https://github.com/papastergiousp-maker/My_Projects/blob/main/MICROSOFTSTOCK.ipynb) |
| 5 | Industrial QC & Financial Risk | What is the cost of production batch failures? | €76K total impact · €56K corrections · €20K critical waste | [Repo](https://github.com/papastergiousp-maker/Industrial-Quality-Control-Financial-Risk-Modeling/blob/main/INDUSTRIAL%20ANOMALY%20DETECTION.ipynb) |
| 6 | Revenue Analysis | Which revenue streams are most profitable? | Revenue stream breakdown with YoY forecasting | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Revenue_Analysis/Revenue.ipynb) |
| 7 | Movies Market Trends | Which genres & studios are most profitable? | Budget vs revenue correlation · genre profitability ranking | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Movies_Market_Trends/Movies_Market_Trends.ipynb) |
| 8 | Cars Fuel Cost Analysis | How does fuel type affect total ownership cost? | Fuel cost-efficiency comparison across vehicle classes | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Cars_Fuel_Cost/Cars%20Fuel%20Cost.ipynb) |
| 9 | Air Quality Analysis | What are the patterns in urban air quality data? | Pollutant concentration trends & seasonal variation | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Air_Quality_Analysis/Air_Quality_Analysis.ipynb) |
| 10 | Hospital Admissions Analysis | What drives hospital admission patterns? | Admission trends by department & seasonal demand spikes | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Hospital_Analysis/Hospital_Admissions.ipynb) |
| 11 | Video Game Sales | Which platforms & genres dominate global sales? | NA vs EU vs JP market split · platform lifecycle analysis | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Video_Game_Sales/%CE%A0%CE%A9%CE%9B%CE%97%CE%A3%CE%95%CE%A9%CE%9D%20VIDEO%20GAMES.ipynb) |
| 12 | Poisson Distribution | Can Poisson model predict video game demand? | Statistical fit analysis for sales forecasting | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Poisson_Distribution/%CE%9A%CE%91%CE%A4%CE%91%CE%9D%CE%9F%CE%9C%CE%97%20POISSON%20VIDEOGAMES.ipynb) |
| 13 | Sales Analysis | What are the key sales performance drivers? | Advanced KPI tracking with trend decomposition | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Sales_Analysis/Sales.ipynb) |
| 14 | Weather Analysis | How does weather correlate with external variables? | Correlation matrix & multivariate regression analysis | [Repo](https://github.com/papastergiousp-maker/Python_Financial_Data_Analytics/blob/main/Weather_Analysis/Weather.ipynb) |
| 15 | Business Analytics Dashboard | Can Python replace a BI tool for live dashboards? | Fully deployed interactive dashboard at phytai.com | [Repo](https://github.com/papastergiousp-maker/My_Projects/blob/main/Business%20Dashboard.ipynb) |

---

## 🏦 End-to-End ETL Pipelines

→ [ETL_Pipelines Repository](https://github.com/papastergiousp-maker/ETL_Pipelines)

Full pipelines from raw data to production dashboard — no pre-cleaned datasets.

| Pipeline | Stack | Link |
|:---------|:------|:-----|
| Eurobank Financial Analysis 2022–2024 | Python · SQL · SQLite · Power BI · DAX | [View](https://github.com/papastergiousp-maker/ETL_Pipelines/tree/main/eurobank-financial-analysis) |

---

*Data sourced from official sources. All financial figures in € million unless stated otherwise.*  
*© 2026 Spyros Papastergiou · [phytai.com](https://phytai.com)*

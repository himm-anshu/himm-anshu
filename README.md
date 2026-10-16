# Hi, I'm Himanshu 👋
### Aspiring Data Analyst | SQL • Python • Excel • Machine Learning • Web Scraping • Power BI • Tableau

I build end-to-end data analytics and machine learning projects — from data cleaning and SQL analysis to predictive modeling and interactive dashboards that generate actionable business insights.

---

## 🔹 Core Expertise

- Data Cleaning & Transformation (Python – Pandas, NumPy)
- SQL Querying & Business KPI Analysis (CTEs, Window Functions, Subqueries)
- Advanced Excel (Power Query, PivotTables, XLOOKUP, Dashboards)
- Exploratory Data Analysis (EDA)
- Statistical Testing (Chi-square, t-test, Effect Size)
- Web Scraping (Selenium, BeautifulSoup)
- Machine Learning (scikit-learn – Logistic Regression, Random Forest, GridSearchCV, Model Evaluation)
- Data Visualization (Matplotlib, Seaborn, Plotly, Tableau, Power BI)
- Dashboard Development & Data Storytelling

---

## 🔹 Featured Projects

### 🤖 Telco Customer Churn Prediction (Machine Learning)
- Built an end-to-end ML pipeline in Python (scikit-learn) to predict churn on a 7,043-record dataset
- Tuned Logistic Regression and Random Forest with equal GridSearchCV effort — including `class_weight` for both — for a fair model comparison rather than tuning only one candidate
- Random Forest selected (0.843 ROC-AUC); optimized the classification threshold to reach 81% churn recall, correctly identifying 302 of 374 actual churners
- Validated an engineered feature for redundancy (found 0.996 correlation with an existing feature) rather than assuming it added value
- 🔗 [Repo](https://github.com/himm-anshu/Telco-Customer-Churn-Prediction)

### 📊 Telco Customer Churn Analysis
- Cleaned and validated 7,043 customer records using Python (Pandas)
- Wrote SQL queries in MySQL to validate and analyze a 26.54% overall churn rate and highest-risk segments
- Ran a chi-square test (contract type vs churn: χ² = 1184.6, p < 0.001, Cramér's V = 0.41) and a t-test (churned customers pay $13.18 more per month, p < 0.001)
- Built an interactive Tableau dashboard (published on Tableau Public) with 3 KPI cards and 6 analytical visualizations
- 🔗 [Repo](https://github.com/himm-anshu/telco-customer-churn-analysis)

### 📦 Amazon India Sales Analysis (Advanced Excel)
- Cleaned a 128,976-row e-commerce sales file in Power Query: removed 959 duplicates, fixed a date column that mixed two formats, and standardised 69 state spellings to 37
- Used XLOOKUP, SUMIFS, UNIQUE/FILTER and PivotTables to analyse revenue by category, state and month, and built an interactive Excel dashboard with KPI cards, 4 charts and slicers
- Found that T-shirts and shirts make up 77% of revenue and that Merchant-fulfilled orders were cancelled more often than Amazon-fulfilled ones (17.4% vs 12.6%)
- 🔗 [Repo](https://github.com/himm-anshu/amazon-india-sales-excel)

### 📚 Book Market Analysis (Web Scraping)
- Scraped 1,000 book records across 50 categories from a scraping-practice site (books.toscrape.com) using Selenium and BeautifulSoup, handling pagination
- Cleaned the data in pandas (price and rating type conversion, validation checks) and excluded 219 books (21.9%) in placeholder categories before category analysis
- Analysed price, rating and category patterns with groupby, correlation and a t-test; built 6 interactive Plotly charts and found no relationship between price and rating (r = 0.028, p = 0.582)
- 🔗 [Repo](https://github.com/himm-anshu/books-scraping-project)

### 🛍️ Customer Shopping Behavior Analytics
- Cleaned and engineered a 3,900-record, 18-field shopping dataset in Python, then loaded it into MySQL via the Table Data Import Wizard
- Wrote SQL queries using CTEs, window functions, and correlated subqueries to segment customers and rank top products
- Built an interactive Power BI dashboard with 4 KPI cards, 6 visualizations, and 4 slicers covering $233K in revenue
- 🔗 [Repo](https://github.com/himm-anshu/Customer-Shopping-Analytics)

### 🏬 Retail Sales Performance Dashboard
- Cleaned a retail transactions dataset in Python, validated it with SQL, and built an interactive Power BI dashboard
- KPI cards for Total Revenue, Profit, Profit Margin, and Average Order Value, filterable by City and Product
- 🔗 [Repo](https://github.com/himm-anshu/retail-sales-powerbi-dashboard)

---

## 🔹 Tools

Python • SQL (MySQL) • scikit-learn • Pandas • NumPy • Selenium • BeautifulSoup • Matplotlib • Seaborn • Plotly • Power BI • Tableau • Excel (Power Query)

---

## 📫 Connect

**LinkedIn:**
https://linkedin.com/in/himanshu-kumar-645b0728a

**Tableau Public:**
https://public.tableau.com/views/telco_churn_dashboard_17882435873900/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# powerbi-sales-dashboard
Interactive Power BI dashboard for end-to-end data transformation, DAX modeling, and business insights visualization.

An end-to-end Data Analytics project featuring an interactive **Microsoft Power BI Desktop** dashboard designed to transform raw data into actionable business insights for decision-making.

Built as part of my Business Intelligence portfolio / skill development in Data Analytics.

## 🎯 Key Objectives

- **Data Cleaning & ETL:** Extract, transform, and clean raw multi-source data using Power Query.
- **Data Modeling:** Design an optimized, high-performance Star Schema model.
- **DAX Measures:** Develop dynamic Key Performance Indicators (KPIs) and custom business logic.
- **Data Visualization:** Create an intuitive, user-friendly, and interactive dashboard following UI/UX best practices.

---

## 🛠️ Tech Stack & Tools

* **Microsoft Power BI Desktop** (Data Modeling, DAX, Dashboard Creation)
* **Power Query** (ETL - Extract, Transform, Load)
* **DAX** (Data Analysis Expressions)
* **Excel / CSV** (Data Sources)

---

## 📐 Project Workflow

1. **Extract, Transform & Load (ETL)**:
   - Imported raw data files.
   - Handled missing values, removed duplicates, and reformatted data types.
   - Built organized Fact and Dimension tables.

2. **Data Modeling**:
   - Created a dynamic Date/Calendar table.
   - Defined 1-to-Many (`1:*`) relationships between dimension and fact tables to enforce a clean Star Schema.

3. **DAX Calculations & Analysis**:
   - Built core aggregation measures (`SUM`, `AVERAGE`, `COUNTROWS`).
   - Implemented Time Intelligence functions (`SAMEPERIODLASTYEAR`, `YTD`) to analyze period-over-period performance.

4. **Dashboard Design**:
   - Designed high-level KPI cards (Revenue, Profit Margin, Order Volumes).
   - Created trend charts and categorical breakdowns.
   - Added interactive slicers (Date range, Product category, Region) for dynamic filtering.

## 📈 Preview

<img width="2559" height="1357" alt="image" src="https://github.com/user-attachments/assets/9edb5c0c-9246-4771-a8bc-955ae0b9d2dc" />
<img width="2559" height="1358" alt="image" src="https://github.com/user-attachments/assets/84f6b430-8182-4315-aba0-e5b3d130cd60" />

## 📁 Repository Structure

```text
├── data/                  # Contains sales_2.csv dataset
├── assets/                # Screenshots, icons, and JSON theme files
├── PowerBI_Project.pbix   # Main Power BI project file
└── README.md              # Project documentation

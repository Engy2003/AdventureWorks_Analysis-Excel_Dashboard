# 📊 AdventureWorks Excel Dashboard

## 🔎 Project Overview
This project showcases a **professional Excel dashboard** built using the AdventureWorks dataset.  
It demonstrates the full workflow of a data analyst, starting from **data cleaning and modeling** to building **interactive dashboards** that deliver clear business insights.  

The project includes:  
- End-to-end data preparation in Excel (Power Query + Power Pivot).  
- A star-schema data model.  
- Custom calculated columns and KPIs.  
- Two fully interactive dashboards with filters, slicers, and navigation buttons.  
- Professional design with custom icons and clear insights.  

---

## 🛠️ Workflow

### 1. Data Preparation
- Imported data from **AdventureWorks.xlsx**.  
- Cleaned and transformed tables in **Power Query**:
  - Removed irrelevant fields, Handled null values.  
  - Created additional calculated columns (e.g., Age Groups).  
- Built a **data model in Power Pivot** by connecting fact and dimension tables:  
  - `FactInternetSales`, `DimProduct`, `DimCustomer`, `DimDate`, `DimSalesTerritory`, `DimGeography`.  
- Structured the model using a **Star Schema** approach for efficient analysis.  

### 2. Dashboard Design
Two dashboards were designed inside Excel with a focus on clarity, interactivity, and actionable insights.  

#### 📌 Page 1: Time Series Dashboard
- **KPIs**:  
  - Total Quantity, Total Cost, Total Revenue, Total Profit, Profit Margin, Number of Transactions.  
  - Each KPI includes a year-over-year comparison (% increase/decrease).  

- **Visualizations & Insights**:  
  - Clustered Column Chart: Total Profit, Revenue, and Transactions across years (2005–2008).  
  - Line chart: Total Profit over months (trend analysis).  
  - Clustered Column Chart: Total Profit by weekday.  
  - Pie chart: Total Profit split between weekdays and weekends.  
  - Custom chart: Total Profit by quarter.

- **Filters**: Year, Country, Month.  
- **Map**: Custom visualization for Total Profit by country.  
- **Navigation Buttons**:  
  - Time Series Dashboard  
  - P & C Analysis  
  - Clear Filters  

---

#### 📌 Page 2: Performance & Category (P & C) Analysis
- **Products Analysis**:  
  - Clustered Bar Chart: Top 5 Products by Total Profit (with % contribution vs Others).  
  - KPIs: Available Products, Sold Products, Unsold Products.  
  - Clustered Bar Chart: Total Profit by Product Color.  
  - Custom chart: Total Profit by product price category (Expensive > $150 vs. Not Expensive).  

- **Customers Analysis**:  
  - Clustered Bar Chart: Top 5 Customers by Total Profit (with % contribution vs Others).  
  - KPIs: Average Customer Age, Total Customers, Total Profit % by Gender (Male/Female).  
  - Clustered Column Chart: Total Profit by Age Groups.  
  - Clustered Bar Chart: Top 5 Cities by Total Profit (with % contribution vs Others).  

- **Filters**: Year, Country.  
- **Design Note**: **Clustered bar/column charts** :used to compare values across categories. 
  Applied overlap and customized colors to highlight the highest values, giving the final chart the appearance of a simplified Bar/column Chart.
- **Navigation Buttons**: Same as Page 1.  

---

## 📂 Repository Structure
- **AdventureWorks.xlsx** → Raw AdventureWorks dataset.  
- **AdventureWorks Excel Dashboard.xlsx** → Final Excel file containing the interactive dashboards.  
- **Icons/** → Custom icons used for dashboard design.  
- **Images/**  
  - `model.png` → Data model diagram.  
  - `Time Analysis.png` → Screenshot of the Time Series Dashboard.  
  - `P & C Analysis.png` → Screenshot of the P & C Dashboard.  
- **Custom_Columns.txt** → Documentation of important calculated columns (e.g., Age Groups).  
- **README.md** → Project documentation.  

---

## 🚀 How to Use
1. Download or clone this repository.  
2. Open **Dashboard.xlsx** in Microsoft Excel (2016 or later recommended).  
3. Explore the dashboards:  
   - Switch between **Time Series** and **P & C Analysis** using the navigation buttons.  
   - Apply slicers and filters (Year, Country, Month) for interactive analysis.  
4. Review KPIs, charts, and insights.  
5. For calculation logic, check **Custom_Columns.txt**.  

---

## 📝 Key Features
- End-to-end ETL workflow inside Excel (Power Query + Power Pivot).  
- Star-schema data model for efficiency.  
- Six key KPIs with year-over-year comparison.  
- Two dashboards:  
  - **Time Series Dashboard** → Trends and time-based insights.  
  - **P & C Analysis** → Product and customer performance breakdown.  
- Advanced Excel visuals (line, Clustered Bar, Clustered column, pie, custom charts, maps).  
- Clear navigation buttons and professional layout.  
- Documented calculated columns for reproducibility.

---

## 📧 Contact
For questions or collaboration:  
- **Email**: engysead498@gmail.com
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/engy-saeed-b47784276/)


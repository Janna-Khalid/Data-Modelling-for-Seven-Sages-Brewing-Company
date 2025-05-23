# Seven Sages Brewing Company - Power BI Sales Analysis Dashboard

This project is part of the **Data Analysis and Visualization with Power BI Nanodegree** by **Udacity**. The goal was to design an intuitive, centralized Power BI report for **Seven Sages Brewing Company**, enabling their CFO to effortlessly monitor top-performing beers and overall profitability across the business.

> ✅ Completed: December 09, 2024

## 📊 Project Overview

Seven Sages Brewing Company, like many growing businesses, faced a common challenge: siloed data across departments. This project brings all that scattered information into a single, cohesive Power BI data model, providing decision-makers with real-time insights into performance, sales, and margins.

By applying strong data modeling and visualization principles, I created a dynamic, interactive dashboard that lays a solid foundation for more advanced reporting needs—including complex DAX measures, scalable data models, and high-level executive summaries.

---

## 🗂️ Data Sources

The data for this project was compiled from multiple departments and formats:

- **Promotional Document**: Provided by the Sales team, includes product names, ratings, and serving sizes.
- **Purchases**: Multiple Excel spreadsheets from Operations detailing purchases.
- **Customer Records**: Exported by IT with updated customer details.
- **Metrics Documentation**: Sales, costs, and servings data maintained by the CFO.

All raw files are stored under the `/source files` directory.

---

## ⚙️ ETL Process (Extract, Transform, Load)

### 🔧 Data Cleanup
- Promoted first rows to headers
- Reviewed and corrected data types
- Renamed ambiguous queries and unclear column headers
- Removed blank rows and unnecessary columns
- Fixed obvious typos impacting results

### 🔗 Data Integration
- **Product Table**: Merged the CFO’s metrics with the SSBC product offerings
- **Sales Table**: Combined all files from the "Monthly Sales Logs" folder
- **Date Table**: Created a dynamic date table with:
  - Calendar Month (Number & Name)
  - Calendar Year
  - Fiscal Period
  - Fiscal Year
  - Fiscal Quarter (e.g. Q2-FY2020)

---

## 🧠 Data Model

![alt text](<Relationships Between Tables.jpg>)


### Fact Table
- **Sales**

### Dimension Tables
- **Products**
- **Customers**
- **Calendar**
- **Exchange Rates**

---

## 📐 Key Measures

- `Total Sales ($USD)`
- `Cost of Sales ($USD)`
- `Gross Profit Margin (%)`
- `Sales ($CAD)`
- `Unit Sales by Product (% in USD)`
- `Gross Profit by Product (% in USD)`

---

## 📈 Report Pages


### 🧾 Tab 1: Sales by Customer
A quarterly summary of sales by **Customer Name** and **Customer Type**.

![alt text](<Sales by Customer.jpg>)

### 📊 Tab 2: Product Performance
A percentage-based breakdown of:
- **Gross Profit** by product
- **Unit Sales** by product

![alt text](<Product Performance.jpg>)


---

## 🚀 Highlights

- Unified data from various departments into one robust data model
- Built a clean, dynamic dashboard tailored for executive use
- Demonstrated core Power BI capabilities including:
  - Data shaping & modeling
  - Relationship management
  - Advanced DAX calculations
  - Visual storytelling


---

## 📎 License

This project was completed for educational purposes as part of the Udacity Nanodegree. Source files provided by Udacity are used under educational fair use.

---

## 🙌 Acknowledgements

Thanks to [Udacity](https://www.udacity.com) for providing the structure, data, and guidance for this insightful and practical capstone project.

# FUTURE_DS_02
Power BI Dashboard analyzing marketing campaign performance and efficiency.
This repository contains my submission for **Task 1** of the FUTURE Data Science & Analytics Internship.  
The goal was to clean a raw sales dataset and build an interactive Power BI dashboard to uncover trends in product sales and customer purchasing behavior.

---

### 🧹 Data Preparation
The raw dataset (`Sales Transaction v.4a.csv`) was cleaned and preprocessed using **Python (pandas)** before analysis.
The Steps I Took:
- Dropped rows with missing critical values (`Date`, `ProductNo`, `ProductName`, `Price`, `Quantity`, `CustomerNo`)
- Converted `Date` to datetime format
- Ensured `Price` and `Quantity` were numeric
- Removed negative or zero values
- Created additional columns for `TotalSales`, `Year`, `Month`, and `Quarter`

- Power BI Dashboard

After cleaning, the data was imported into Power BI to build a report that tracks:
Total Sales and Quantity over time
Top-performing products
Revenue distribution by month and quarter
Key performance indicators (KPIs) for sales and average price
The visuals were designed to give a clear overview of performance and seasonality.

⚙️ Tools Used
Python (pandas) – data cleaning
Power BI – dashboard creation
Power Query – initial exploration

# Vehicle Sales Performance & Analysis

## 📌 Project Overview

This project analyzes **8,000+ vehicle sales transactions** using Google Sheets to understand sales performance, pricing patterns, discounts, customer and dealer activity, and vehicle-level trends.

The project combines a **Vehicle Sales dataset** with a **Vehicle Master dataset** containing vehicle specifications and categories. An interactive dashboard was created to present key KPIs and business insights.

---

## 🎯 Problem Statement

The vehicle sales data contained missing values, inconsistent data formats, and vehicle information stored across separate datasets. The objective was to clean and integrate the data and analyze sales performance across brands, models, segments, states, fuel types, and dealers.

---

## 📂 Dataset

### Vehicle Sales Dataset

**8,000+ records**

Key columns:

* Sale_ID
* Sale_Date
* Vehicle_ID
* Dealer_ID
* Customer_ID
* State
* Condition_Score
* Odometer_KM
* MMR_Value
* Discount
* Selling_Price

### Vehicle Master Dataset

**500 vehicle records**

Key columns:

* Vehicle_ID
* Brand
* Model
* Trim
* Segment
* Fuel_Type
* Transmission
* Engine_CC
* Manufacturing_Year
* Default_Color

---

## 🛠️ Tools & Technologies

* Google Sheets
* XLOOKUP
* SUMIFS
* COUNTIFS
* AVERAGEIFS
* QUERY
* Pivot Tables
* Calculated Fields
* Charts
* Slicers
* Interactive Dashboard

---

## 🔄 Methodology

### 1. Data Collection

Imported the vehicle sales and vehicle master datasets into Google Sheets.

### 2. Data Cleaning

* Handled missing values in State, Odometer, and Discount fields.
* Standardized inconsistent State names and formatting.
* Checked Sale_ID uniqueness.
* Preserved the original raw datasets separately for reference.

### 3. Data Integration

Used **XLOOKUP** to combine vehicle attributes such as Brand, Model, Segment, Fuel Type, Transmission, and Manufacturing Year with the sales transaction data.

### 4. Feature Creation

Created additional analytical fields including:

* Price Variance
* Discount %
* Vehicle Age
* Mileage Category
* Price Category
* Sale Year
* Sale Month

### 5.KIP's Calculated

Calculated required KPI's

* Total Sales
* Vechiles_sold
* Avgerage selling price
* Total Discount
* Average discount
* Average Condition
* Toyoto Sales
* Toyota Vechiles count
* Avg Toyota Selling price

  <img width="202" height="173" alt="image" src="https://github.com/user-attachments/assets/c49242fa-5e30-4175-8202-4900064cc7e6" />

  

### 6. Data Analysis

Used formulas, QUERY, and Pivot Tables to analyze:

* Sales by Brand
* Sales by Segment
* Sales by State
* Fuel Type performance
* Dealer performance
* Monthly sales trends

  

### 7. Dashboard Development

Created an interactive dashboard containing:

* Total Sales
* Vehicles Sold
* Average Selling Price
* Average Discount %
* Monthly Sales Trend
* Sales by Brand
* Sales by Segment
* Top Models
* Fuel Type Analysis
* Dealer Performance
* State Performance
* Interactive Slicers

---

## 📊 Key Findings

The analysis was used to identify:

* Top-performing vehicle brands and models.
* High-performing vehicle segments.
* States and dealers generating higher sales.
* Monthly sales trends and changes in performance.
* Differences between Selling Price and MMR Value.
* Discount patterns across vehicles and categories.
* Sales distribution across fuel types and transmission types.

---

## 💼 Business Impact

The dashboard provides a centralized view of vehicle sales performance and can support:

* Pricing decisions
* Discount optimization
* Inventory planning
* Dealer performance analysis
* Identification of high-performing vehicle categories
* Sales trend monitoring

---

## 📁 Project Structure

```text
Vehicle-Sales-Analysis/
│
├── Dataset/
│   ├── Vehicle_Sales_8000.csv
│   └── Vehicle_Master_500.csv
│
├── Dashboard/
│   └── Vehicle_Sales_Dashboard.pdf
│
└── Screenshots/
|  └── dashboard.png
├── README.md
```

---

## 📈 Dashboard Preview

Add a screenshot of your final Google Sheets dashboard here.

<img width="896" height="391" alt="image" src="https://github.com/user-attachments/assets/5adc616f-4264-45be-b029-359a5ab2504c" />
<img width="853" height="466" alt="image" src="https://github.com/user-attachments/assets/9295c951-2e8e-42b8-a59c-1ceee88bf5ef" />



## 🧠 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Integration
* Exploratory Data Analysis
* Spreadsheet Analysis
* Lookup Functions
* Conditional Aggregation
* Pivot Table Analysis
* Data Visualization
* Dashboard Development
* Business Insights

---

## 👩‍💻 Author

**Adhi Nikhitha**

Computer Science Engineering Student | Aspiring Data Analyst

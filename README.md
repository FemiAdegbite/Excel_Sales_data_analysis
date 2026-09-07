# Excel_Sales_data_analysis
# Excel Sales Data Analysis & Dashboard

## Project Overview

**Excel_Sale_Data_Analysis** is an Excel-based sales data analysis and dashboard project focused on transforming raw sales records into meaningful business insights.

The project uses **Microsoft Excel and Pivot Tables** to analyze sales performance across product categories, regions, months, order priorities, and sales channels. The analysis also includes calculated metrics for profitability and order performance.

The workbook contains a sales dataset with **10,000 records** covering the period **2015–2022**, along with supporting calculations, Pivot Tables, and a sales dashboard.

---

## Problem Statement

Businesses generate large volumes of sales data, but raw records alone do not provide an easy way to identify important performance trends.

This project addresses the need to analyze sales data and answer questions such as:

* Which product categories generate the highest revenue and profit?
* Which regions perform best?
* Which months generate the most revenue?
* Which sales channel has the highest number of orders?
* How many orders were cancelled?
* What patterns can be identified from the sales data?

The goal was to organize and analyze the available sales information and present the results in a clear, business-friendly format.

---

## Objectives

The main objectives of this project were to:

* Analyze sales performance across different product categories.
* Compare revenue and profitability across regions.
* Examine monthly revenue trends.
* Analyze sales performance by sales channel.
* Identify the most profitable product category.
* Identify the most profitable region.
* Determine the most frequently used sales channel.
* Analyze cancelled orders.
* Use Pivot Tables and Excel calculations to summarize the data.
* Present key findings through an interactive sales dashboard.

---

## Dataset / Data Source

The project workbook contains **10,000 sales records** with information including:

* Region
* Country
* Item Type
* Sales Channel
* Order Priority
* Order Date
* Order ID
* Ship Date
* Units Sold
* Unit Price
* Unit Cost
* Total Revenue
* Total Cost
* Total Profit

The workbook also contains an **Extra Data** sheet with additional sales records.

**Data Source:** [Add dataset source/link if available]

---

## Tools & Technologies Used

| Tool                | Purpose                                                                          |
| ------------------- | -------------------------------------------------------------------------------- |
| **Microsoft Excel** | Data analysis, calculations, organization and dashboard development              |
| **Pivot Tables**    | Summarizing and analyzing revenue by month, item type, region and order priority |
| **Excel Formulas**  | Calculating revenue, cost, profit and other performance metrics                  |
| **Excel Dashboard** | Presenting key sales insights visually                                           |

---

## Process / Methodology

The project followed a structured Excel-based data analysis workflow:

### 1. Data Preparation

The sales data was organized into an Excel table containing the available sales attributes and calculated financial metrics.

The dataset includes fields for units sold, unit price, unit cost, revenue, cost and profit, allowing sales performance to be evaluated from different perspectives.

### 2. Data Analysis

The data was analyzed across several dimensions, including:

* Month
* Product/Item Type
* Region
* Order Priority
* Sales Channel

### 3. Pivot Table Analysis

Pivot Tables were created to summarize revenue by:

* Month
* Item Type
* Region
* Order Priority

These summaries made it easier to compare sales performance and identify high-performing areas.

### 4. Profitability Analysis

Excel calculations were used to determine total profit by product category and region.

The analysis was then used to identify:

* Most profitable item
* Most profitable region
* Most profitable sales channel

### 5. Dashboard Development

The analysis was presented through an Excel sales dashboard titled:

**PRODUCT SALES DASHBOARD (2015–2022)**

The dashboard brings together the major findings from the analysis into a visual business reporting format.

---

## Key Analysis / Work Done

### Revenue Analysis by Month

Monthly revenue was summarized using a Pivot Table to identify changes in sales performance throughout the year.

Based on the dataset, **January recorded the highest total revenue among the months analyzed**.

### Revenue Analysis by Item Type

Revenue was analyzed across 12 item categories:

* Baby Food
* Beverages
* Cereal
* Clothes
* Cosmetics
* Fruits
* Household
* Meat
* Office Supplies
* Personal Care
* Snacks
* Vegetables

**Household** generated the highest total revenue among the item categories.

### Profitability by Item Type

Profit was calculated for each item category.

**Cosmetics** was identified as the **most profitable item type**, generating approximately:

**$744.83 million in total profit**

### Revenue Analysis by Region

Revenue was compared across seven regions:

* Asia
* Australia and Oceania
* Central America and the Caribbean
* Europe
* Middle East and North Africa
* North America
* Sub-Saharan Africa

**Europe** recorded the highest total revenue and was also identified as the **most profitable region**.

### Sales Channel Analysis

The dataset contains two sales channels:

* Online
* Offline

The analysis showed:

* **Offline:** 5,008 orders
* **Online:** 4,992 orders

Therefore, **Offline** was the top sales channel by number of sales records.

### Cancelled Orders

The analysis identified:

**2,348 cancelled orders**

This metric was included as part of the key performance calculations.

---

## Key Findings / Results

The major findings from the analysis include:

* **Cosmetics** was the most profitable item type, generating approximately **$744.83 million** in profit.
* **Europe** was the most profitable region, generating approximately **$1.53 billion** in profit.
* **Household** recorded the highest total revenue among the product categories.
* **Offline** was the leading sales channel by number of sales records, with **5,008** records.
* **2,348 orders** were identified as cancelled.
* **January** recorded the highest monthly revenue in the dataset.
* The analysis provides a consolidated view of sales performance across products, regions, months and sales channels.

---

## Recommendations

Based on the findings from the analysis, the following actions could be considered:

1. **Focus on high-profit products**
   Continue monitoring high-performing categories such as Cosmetics and identify opportunities to maintain or increase their profitability.

2. **Strengthen performance in high-performing regions**
   Europe demonstrated strong revenue and profitability performance and could be evaluated for further growth opportunities.

3. **Investigate cancelled orders**
   The number of cancelled orders suggests an opportunity to investigate the causes of cancellations and identify ways to reduce them.

4. **Evaluate sales channel performance**
   Since Offline sales slightly exceeded Online sales in the dataset, businesses could compare the profitability and customer behavior of both channels before allocating additional resources.

5. **Monitor seasonal sales patterns**
   Monthly revenue analysis can help identify periods of stronger demand and support better sales planning and resource allocation.

---

## Visualizations

The Excel workbook includes a sales dashboard supported by Pivot Table summaries.

The analysis includes visual reporting of:

* Monthly Revenue
* Revenue by Item Type
* Revenue by Region
* Revenue by Order Priority
* Key Profitability Metrics
* Sales Channel Performance
* Cancelled Orders

### Dashboard Preview

[Add dashboard screenshot here]

Example:

```text
![Sales Dashboard](images/sales-dashboard.png)
```

---

## Project Files

The main workbook contains the following sheets:

| Sheet                         | Description                                          |
| ----------------------------- | ---------------------------------------------------- |
| **Sales Data**                | Main sales dataset containing 10,000 records         |
| **Extra Data**                | Additional sales data included in the workbook       |
| **Month by Revenue**          | Pivot Table summarizing revenue by month             |
| **Item Type by Revenue**      | Pivot Table summarizing revenue by item category     |
| **Region by Revenue**         | Pivot Table summarizing revenue by region            |
| **Order Priority by Revenue** | Pivot Table summarizing revenue by order priority    |
| **Calculations**              | Excel calculations for profitability and key metrics |
| **Dashboard**                 | Final product sales dashboard                        |

### Suggested Repository Structure

```text
Excel_Sale_Data_Analysis/
│
├── Sales Dashboard in Excel.xlsx
├── README.md
│
└── images/
    └── sales-dashboard.png
```

[Adjust the file names and folder structure to match the actual GitHub repository.]

---

## How to Use / Run the Project

Since this is an Excel-based project, no programming environment is required.

### Steps

1. Download or clone this repository.
2. Open the Excel workbook:
   `Sales Dashboard in Excel.xlsx`
3. Navigate to the **Sales Data** sheet to explore the underlying data.
4. Review the Pivot Table sheets to explore the summarized analysis.
5. Open the **Calculations** sheet to review the profitability and performance calculations.
6. Open the **Dashboard** sheet to view the final sales dashboard.
7. Use the workbook's Pivot Tables and Excel features to further explore the data.

> **Note:** If Pivot Tables are not displaying current results after opening the workbook, refresh the Pivot Tables in Excel.

---

## Project Link / Dashboard Link

**GitHub Repository:** [Add project link]

**Dashboard:** [Add dashboard link if available]

---

## Skills Demonstrated

This project demonstrates practical skills in:

* Microsoft Excel
* Data Analysis
* Data Cleaning and Organization
* Pivot Tables
* Data Aggregation
* Revenue Analysis
* Profitability Analysis
* Business Reporting
* Dashboard Development
* Data Visualization
* Business Insight Generation

---

## About the Author

### Adegbite Femi Gbenga

I am a **Data Analyst and Data & Administrative Professional** with a background in **Demography and Social Statistics** and practical experience working with data, CRM systems, reporting, customer records and administrative processes.

My technical experience includes **Excel, SQL, Power BI, Google Sheets, Salesforce CRM, SPSS and Stata**, with a growing focus on data analytics and business intelligence.

I enjoy turning raw data into clear insights that can support better business decisions.

### Connect With Me

* **LinkedIn:** [linkedin.com/in/femi-adegbite-6bab38376](https://www.linkedin.com/in/femi-adegbite-6bab38376/)
* **GitHub:** [github.com/FemiAdegbite](https://github.com/FemiAdegbite)
* **Email:** [adegbitefemi.g@gmail.com](mailto:adegbitefemi.g@gmail.com)

---

## Conclusion

The **Excel Sales Data Analysis & Dashboard** project demonstrates how Excel can be used to transform raw sales records into structured analysis and actionable business insights.

Through Pivot Tables, Excel calculations and dashboard reporting, the project provides an overview of revenue, profitability, regional performance, product performance, sales channels and cancelled orders.

The project also demonstrates practical data analysis skills, from organizing and summarizing raw data to communicating findings through a business-focused dashboard.

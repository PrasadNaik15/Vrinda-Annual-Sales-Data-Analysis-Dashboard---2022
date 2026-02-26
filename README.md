# Vrinda-Annual-Sales-Data-Analysis-Dashboard---2022
**Project Overview**

This project analyzes the annual sales performance of Vrinda Store for the year 2022 using Microsoft Excel. The goal was to clean raw transactional data, handle inconsistencies, and generate business insights through an interactive dashboard.


**Dataset Information**
The dataset contains order-level transactional data including:

-Order ID

-Order Date

-Customer Age

-Gender

-State

-Product Category

-Sales Amount

-Order Status

The raw dataset contained missing values, inconsistencies, and formatting issues which were cleaned before analysis.


**Data Cleaning & Preprocessing Steps**

The following steps were performed to ensure data quality and accuracy:

**1️. Data Inspection**

Checked column data types (text, date, numeric)

Identified missing values and blank rows

Verified duplicate Order IDs

**2️. Handling Missing Values**

Removed rows with critical missing values (Order ID, Sales Amount)

Replaced missing Age values using median age

Standardized missing categorical values (e.g., replaced blanks with “Unknown” where applicable)

**3️. Removing Duplicates**

Used Excel’s Remove Duplicates feature on Order ID

Ensured unique transaction records

**4️. Data Standardization**

Standardized gender values (e.g., Male/male/M → Male)

Corrected inconsistent state names

Unified product category labels

**5️. Date Formatting**

Converted Order Date to proper date format

Extracted Month and Year columns for time-based analysis

**6️. Feature Engineering**

Created Age Group column (e.g., 18–29, 30–49, 50+)

Created Revenue KPI column for summary calculations

Generated Month Name for dashboard visualization

**7️. Data Validation**

Cross-verified total revenue with pivot totals

Checked for negative or invalid sales values

Ensured no blank categorical fields remained



**Exploratory Data Analysis (EDA)**

Performed analysis using Pivot Tables and Charts:

-Revenue by State

-Revenue by Gender

-Age Group Segmentation

-Monthly Sales Trends

-Product Category Performance

-Order Status Distribution



**Dashboard Features**

Built an interactive Excel dashboard including:

-Total Revenue KPI

-Total Orders KPI

-State-wise Sales Analysis

-Customer Age & Gender Segmentation

-Monthly Sales Trend Chart

-Product Category Performance



**Key Insights**

Top 3 states contributed approximately 35% of total revenue.

-Age group 30–49 generated nearly 50% of total orders.

-Certain product categories showed higher repeat purchase rates.

-Identified peak sales months and seasonal demand patterns.



**Tools & Techniques Used**

-Microsoft Excel

-Pivot Tables

-Data Cleaning & Transformation

-Data Validation

-Dashboard Design

-KPI Tracking



**Project Outcome**

Successfully transformed raw, unstructured sales data into a clean and structured dataset, enabling meaningful business insights and interactive reporting for decision-making.

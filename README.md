# UPI Transaction Analysis
#### Dashboard Link: https://public.tableau.com/app/profile/kritika.khanduri/viz/UPITransactionDashboard_17871271182410/Dashboard1

# Project Preview
This project presents an interactive UPI Transaction Analysis Dashboard created using Tableau. The dashboard provides a visual analysis of transaction amounts across different cities, age groups, payment methods, and merchants.

The dashboard includes interactive filters that allow users to explore transaction patterns based on:

Bank Name Received
Currency
Device Type
Payment Mode
Purpose

# Problem Statement

With the increasing use of digital payments, analyzing UPI transaction data can help identify transaction patterns, understand customer behavior, and compare transaction activity across different cities, payment methods, and merchants.

The objective of this project is to develop an interactive Tableau dashboard that provides a clear overview of UPI transaction activity and helps users analyze transaction amounts across different dimensions.

The dashboard focuses on:

Understanding transaction distribution across different age groups.
Comparing transaction amounts across cities.
Analyzing transaction amounts by payment method.
Comparing merchant-wise transaction amounts.
Providing interactive filtering for detailed analysis.
# Dashboard Overview

The UPI Transaction Analysis Dashboard combines multiple visualizations into a single interactive dashboard.

The dashboard contains:

### 1. Transaction Analysis by Age Group

A card-style visualization was created to display the number of transactions across different age groups.

     The dashboard shows:

     Age Group	Number of Transactions
     Age Group 1	3,000
     Age Group 2	5,000
     Age Group 3	12,000

This visualization provides a quick comparison of transaction activity across the defined age groups.

### 2. Total Transaction by Cities

A geographical map was created using Tableau's map visualization to display transaction amounts across major cities.

     The cities represented in the dashboard include:

     City	Total Transaction Amount
     Mumbai	3,027,447
     Delhi	3,019,473
     Hyderabad	2,950,376
     Bangalore	2,939,342

The map provides a geographical view of transaction activity and makes it easier to compare transaction amounts between cities.

### 3. Total Transaction by Payment Method & Merchant

A column chart was created to compare transaction amounts across different payment methods and merchants.

     The payment methods included are:

     Phone Number
     QR Code
     UPI ID

#### The merchants included are:

     Amazon
     Flipkart
     IRCTC
     Swiggy
     Zomato

#### The visualization helps compare how transaction amounts vary between merchants for each payment method.

Phone Number
    Merchant 	        Transaction Amount
    Amazon	            840,990
    Flipkart	        664,198
    IRCTC	            822,290
    Swiggy	            826,386
    Zomato	            825,061

QR Code

    Merchant	        Transaction Amount
    Amazon	            820,360
    Flipkart	        671,388
    IRCTC	            797,281
    Swiggy	            836,340
    Zomato	            854,011

UPI ID

    Merchant	        Transaction Amount
    Amazon	            854,011
    Flipkart	        651,510
    IRCTC	            858,094
    Swiggy	            796,500
    Zomato	            837,318

#### Note: The values shown in this visualization represent the sum of transaction amounts, as configured in the Tableau worksheet.

Filters Used

Interactive filters were added to make the dashboard dynamic and allow users to analyze specific segments of the data.

#### Bank Name Received

    Allows users to filter transactions according to the receiving bank.

#### Currency

    Allows analysis based on the transaction currency.

#### Device Type

    Provides transaction analysis based on the device used.

#### Payment Mode

    Allows users to explore transactions according to the selected payment mode.

#### Purpose

    Allows users to analyze transactions based on their purpose.

### These filters can be used individually or together to perform more focused analysis.

# Steps Followed

### Step 1: Data Preparation

    The UPI transaction dataset was connected to Tableau for analysis.

### Step 2: Data Exploration

    The available dimensions and measures were explored to identify relevant fields for transaction analysis.

### Step 3: Age Group Analysis

    The Age Groups field was used to categorize customers into different age groups.

## -Snap of a card-style visualization was created to display the number of transactions for each age group.

![Card Visual](images/Screenshot%202026-09-05%20151619.png)

### Step 4: Geographic Analysis

    The City field was used with Tableau's geographic capabilities to create a map visualization.

## -Snap of a map visual was created to display transaction amounts across major cities.

![Map Visual](images/Screenshot%202026-09-05%20170837.png)

### Step 5: Payment Method Analysis

The Payment Method field was used to divide transactions into:

    Phone Number
    QR Code
    UPI ID

### Step 6: Merchant Analysis

    The Merchant Name field was added to compare transaction amounts across:

    Amazon
    Flipkart
    IRCTC
    Swiggy
    Zomato
### Step 7: Column Chart Creation

    A column chart was created using Payment Method and Merchant Name along with the SUM(Amount) measure.

This allowed transaction amounts to be compared across payment methods and merchants.

## -Snap of a column chart was created to display transaction amounts to be compared across payment methods and merchants.

![Column Chart](images/Screenshot%202026-09-05%20170950.png)

### Step 8: Interactive Filters

The following filters were added to the worksheets/dashboard:

    Bank Name Received
    Currency
    Device Type
    Payment Mode
    Purpose
### Step 9: Dashboard Creation

The Map Visual, Card Visual, and Column Chart were combined into a single Tableau dashboard.

## -Snapshot of Dashboard 
![UPI Dashboard](images/Screenshot%202026-08-19%20135201.png)
### Step 10: Dashboard Formatting

Titles, labels, colors, spacing, and layout were formatted to make the dashboard easier to understand and visually organized.

# Key Insights

#### The dashboard provides several useful insights into the UPI transaction data.

### 1. Transaction Activity by Age Group

The highest transaction count is observed in Age Group 3, with 12,000 transactions, followed by Age Group 2 with 5,000 transactions and Age Group 1 with 3,000 transactions.

This indicates that the third age group contributes the highest transaction activity among the defined groups.

### 2. City-wise Transaction Amount

Among the cities displayed:

Mumbai records the highest transaction amount at 3,027,447.
Delhi follows with 3,019,473.
Hyderabad records 2,950,376.
Bangalore records 2,939,342.

Mumbai therefore has the highest transaction amount among the cities represented in the dashboard.

### 3. Payment Method & Merchant Analysis

The column chart shows differences in transaction amounts across payment methods and merchants.

For example:

##### Phone Number: Amazon records 840,990, while Flipkart records 664,198.
##### QR Code: Zomato records the highest amount among the displayed merchants at 854,011.
##### UPI ID: IRCTC records the highest displayed amount at 858,094.
##### Flipkart shows comparatively lower transaction amounts across all three payment methods.


These comparisons help identify merchants and payment methods with relatively higher transaction activity.

# Dashboard Features

#### The dashboard provides:

    📊 Age-group transaction analysis
    🌍 City-wise geographical analysis
    📈 Payment method comparison
    🏪 Merchant-wise transaction analysis
    🔎 Interactive filters
    📱 Device-based filtering
    💱 Currency-based filtering
    🏦 Bank-wise filtering
    🎯 Purpose-based filtering
    🎨 Interactive Tableau visualizations

#  Tools & Technologies
       Tools & Technologies
       Tableau
       Data Visualization
       Data Analysis
       Interactive Dashboards
       Geographical Mapping
        
# Conclusion

The UPI Transaction Analysis Dashboard provides an interactive way to explore transaction patterns across age groups, cities, payment methods, merchants, banks, currencies, device types, and transaction purposes.

By combining geographical mapping, card visualizations, and comparative column charts, the dashboard transforms transaction data into an easy-to-understand visual analysis.

#### This project demonstrates practical skills in Tableau, data visualization, dashboard development, interactive filtering, and analytical storytelling.




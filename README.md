# Snapdeal Product Analysis – Power BI

This project was completed as part of my Data Analytics internship. I used Snapdeal product data to analyze pricing, discounts, ratings, reviews, promotions, inventory risk, and product price ranges.

The project was created using Power BI, Power Query and DAX.

## About the Project

The main purpose of this project was to understand the product data and find useful patterns that could help with pricing, promotions, customer satisfaction and inventory-related decisions.

The analysis was divided into six tasks.

## Tasks Completed

### 1. Pricing vs Satisfaction Analysis

Analyzed product price, ratings, estimated sales and risk score to identify products that may need attention.

### 2. Promotion Effectiveness

Compared promotional and non-promotional products based on their discount levels.

The average baseline discount was **14.67%**, while the average promotion discount was **69.65%**, giving a promotional lift of **54.99 percentage points**.

### 3. Discount vs Rating Analysis

Used a scatter plot to compare discounts and product ratings, while also considering review volume.

The regression slope was approximately **0.01**, showing that the relationship between discount and rating was very weak.

### 4. Financial Risk Analysis

Created a financial risk KPI using discount, rating and estimated stock value.

The calculated financially at-risk inventory value was approximately **25.40%**.

### 5. Trust-Weighted Rating

Created a trust-weighted rating using product rating, review count and estimated return rate.

The result was compared with the normal average rating and review-weighted rating.

### 6. Dynamic Price Banding

Created price bands using the 30th and 70th percentiles.

Products are classified as:

- Low
- Medium
- High

The price thresholds change when filters such as category or brand are applied.

## Tools Used

- Power BI
- Power Query
- DAX
- CSV

## Dataset

The project uses a Snapdeal product dataset containing information such as:

- Product name
- Brand
- Category
- Price
- Discount
- Rating
- Review count
- Seller
- Product URL
- Stock-related fields

The dataset is provided separately through Google Drive as required for the internship submission.

## Project Files

- `Snapdeal Analysis.pbix` – Power BI project
- `DAX_Calculations.txt` – DAX calculations used in the project
- `Images` – Screenshots of the completed tasks
- `Report` – Final internship report

## Limitations

The dataset was collected as a product-level snapshot, so it does not contain enough historical data for a true 30-day trend analysis.

Some values used in the analysis, such as estimated sales, stock value and return rate, were derived from the available data and should be treated as estimates rather than actual company figures.

## What I Learned

Through this project, I worked with:

- Data cleaning and preparation
- Power Query
- DAX calculations
- Power BI visuals
- KPI creation
- Data analysis
- Business-oriented interpretation of data

## Project Status

Completed as part of my Data Analytics internship.

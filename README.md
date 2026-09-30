# Luxury & Lifestyle Category Analytics

## Project Overview

This project analyzes e-commerce transaction data to understand **category demand, pricing patterns, customer value, product portfolio performance, assortment breadth, seasonality, and sales-channel behavior**.

The analysis is designed from a **category-management and business decision-making perspective**, using data to identify patterns that can support assortment, pricing, customer retention, and seasonal planning decisions.

## Business Objective

The objective is to answer questions such as:

- Which categories contribute most to transaction volume and sales value?
- How does observed price positioning relate to transaction activity?
- Which customer segments contribute the most normalized sales value?
- Which product families drive the highest demand?
- How does assortment breadth relate to demand per variant?
- Which months show higher historical transaction activity?
- How does transaction and sales-value contribution differ across sales channels?

## Dataset

The primary dataset is the **H&M Personalized Fashion Recommendations** dataset.

It contains:

- Customer information
- Product/article information
- Transaction events
- Product categories and departments
- Normalized transaction prices
- Sales-channel identifiers

The transaction dataset contains approximately **31.79 million transaction events**.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Excel
- Power BI
- Git/GitHub

## Analysis Modules

1. **Category & Pricing Analysis**
2. **Customer RFM Segmentation**
3. **Product Portfolio Analysis**
4. **Assortment Breadth Analysis**
5. **Seasonality Analysis**
6. **Sales Channel Analysis**
7. **Business Recommendations**

## Technical Approach

### Data Processing

Large transaction data was processed using **Pandas chunks** instead of loading the entire dataset into memory at once.

The analysis created reusable processed datasets for:

- Monthly transaction trends
- Customer RFM segments
- Purchase frequency
- Price bands
- Category pricing
- Category × price-band analysis
- Product-family demand
- Product portfolio classification
- Assortment breadth
- Sales-channel contribution

### Dashboard

The final analysis is presented through a **four-page Power BI dashboard**:

1. **Executive Overview** — overall transaction scale, category contribution, channel mix, and customer value.
2. **Pricing & Category** — price-band behavior and category-level pricing/demand patterns.
3. **Customer Analytics** — RFM segmentation, customer contribution, and purchase frequency.
4. **Product Portfolio** — product-family demand, portfolio positioning, and assortment breadth.

## Project Structure

```text
Luxury_Lifestyle_Category_Analytics/
│
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── excel/
│
├── sql/
│
├── notebook/
│
├── powerbi/
│   └── data/
│
├── reports/
│
└── docs/
    └── README.md
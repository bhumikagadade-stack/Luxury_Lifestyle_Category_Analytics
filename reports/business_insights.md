# Business Insights

## 1. Executive Summary

This analysis examines 31.79 million transaction events recorded between September 20, 2018 and September 22, 2020. The analysis focuses on pricing behavior, category demand, customer value, product portfolio performance, assortment breadth, seasonality, and sales-channel mix.

The transaction price field is normalized, so sales-value figures in this analysis represent a **normalized sales-value proxy rather than actual revenue in currency**.

### Key Findings

- The dataset contains approximately **31.79 million transaction events** across **1.36 million unique customers**.
- **Garment Upper body** accounts for the largest transaction share at approximately **39.5%**.
- **Very High price-band transactions** represent about **19.7% of transactions but 40.1% of normalized sales value**.
- **Champions** represent approximately **25.3% of customers and 67.2% of normalized sales value**.
- **Highly Frequent customers** represent approximately **22.2% of customers but 71.4% of normalized sales value**.
- The **Jade HW Skinny Denim TRS** product family has the highest transaction volume, with approximately **168K transaction events across 19 variants**.
- Historical transaction activity is strongest around **June and July**, while February and December show lower average monthly activity.
- **Channel 2** accounts for approximately **70.4% of transaction events and 75.6% of normalized sales value**. The dataset does not provide a verified business label for the channel IDs.

These findings are descriptive and identify patterns for business investigation; they do not establish causal relationships.

## 2. Category & Pricing Insights

### 2.1 Category Demand

Garment Upper body is the largest category by transaction volume, contributing approximately **39.5% of transaction events** and **38.3% of normalized sales value**.

Garment Lower body contributes approximately **22.2% of transactions but 26.2% of normalized sales value**, indicating that its value contribution is higher than its transaction contribution.

Garment Full body contributes approximately **11.2% of transactions and 14.5% of normalized sales value**.

Shoes have a relatively small transaction share of approximately **2.4%**, but contribute around **3.3% of normalized sales value**.

Accessories show the opposite pattern: approximately **5.0% of transactions but only 2.8% of normalized sales value**.

### 2.2 Price Architecture

The Very High price band represents approximately **19.7% of transaction events but 40.1% of normalized sales value**.

In contrast, the Very Low price band represents approximately **21.2% of transactions but only 7.4% of normalized sales value**.

This indicates that transaction volume and value contribution are not evenly distributed across the observed price bands.

### 2.3 Category–Price Relationship

The category-level analysis shows different price profiles:

- **Shoes** have the highest average observed price among the major product groups.
- **Garment Full body** and **Garment Lower body** also have relatively high average observed prices.
- **Accessories** and **Socks & Tights** have lower average observed prices.
- Lower-body and full-body categories contribute a larger share of normalized sales value than their transaction share, while accessories show the reverse pattern.

### Business Implications

- Higher-value categories such as **Garment Lower body, Garment Full body, and Shoes** can be investigated for assortment depth and pricing opportunities.
- The strong normalized-value contribution of the Very High price band suggests that higher-priced products should be examined for their role in the category portfolio.
- Categories with high transaction volume but relatively lower value contribution can be evaluated for opportunities to increase basket value through assortment and cross-category merchandising.
- These findings should not be interpreted as evidence that higher prices cause higher sales value because the dataset does not contain sufficient information to establish causality, actual margins, discounts, or product costs.

## 3. Customer Insights

### 3.1 Customer Value Concentration

The RFM analysis shows a strong concentration of normalized sales value among higher-value customer segments.

**Champions** account for approximately **25.3% of customers but 67.2% of normalized sales value**.

**Loyal Customers** represent approximately **8.8% of customers and 12.5% of normalized sales value**.

In comparison, **Low Engagement** customers represent approximately **37.8% of customers but only 6.2% of normalized sales value**.

**At Risk** customers account for approximately **14.7% of customers and 10.4% of normalized sales value**.

### 3.2 Purchase Frequency

Highly Frequent customers represent approximately **22.2% of customers but 71.4% of normalized sales value**.

One-time customers represent approximately **9.7% of customers but only 0.6% of normalized sales value**.

The data therefore shows a strong association between purchase frequency and normalized customer sales value.

### Business Implications

- High-value and highly frequent customers can be prioritized for **retention and personalized merchandising analysis**.
- At Risk customers can be investigated for potential **reactivation opportunities**, particularly by examining their historical product and category preferences.
- Low Engagement customers represent a large customer population, so their behavior can be analyzed to understand barriers to repeat purchasing.
- Customer segments can be used to support **targeted campaigns, assortment recommendations, and retention strategies**.
- Because the analysis does not include profit margin, customer acquisition cost, or actual customer lifetime value, these segments should be treated as **behavioral/value proxies rather than profitability segments**.

## 4. Product Portfolio Insights

### 4.1 Product Family Demand

The **Jade HW Skinny Denim TRS** product family has the highest transaction volume, with approximately **168,052 transaction events across 19 article variants**.

The **Luna skinny RW** family follows with approximately **143,216 transaction events across 34 variants**.

Other high-volume product families include **Timeless Midrise Brief, Tilly (1), Cat Tee., and Simple as That Triangle Top**.

This indicates that demand is concentrated among a subset of product families rather than being evenly distributed across the catalog.

### 4.2 Portfolio Positioning

The portfolio matrix classifies product families using their relative transaction-share and normalized-sales-value-share positions.

Among product families with at least 1,000 transaction events:

- High Volume / High Value families contribute approximately **72.7% of transactions and 73.2% of normalized sales value**.
- High Volume / Lower Value families contribute approximately **8.8% of transactions and 4.7% of normalized sales value**.
- Lower Volume / High Value families contribute approximately **4.7% of transactions and 9.4% of normalized sales value**.
- Lower Volume / Lower Value families contribute approximately **13.8% of transactions and 12.8% of normalized sales value**.

The portfolio classification is based on median thresholds, so the similar number of product families across some segments is a mathematical consequence of the classification method rather than an independent business finding.

### 4.3 Assortment Breadth

Average transaction demand per variant decreases as product-family variant breadth increases:

| Variant Breadth | Avg. Transactions per Variant |
|---|---:|
| 1–2 variants | 1,347 |
| 3–5 variants | 874 |
| 6–10 variants | 763 |
| 11–20 variants | 728 |
| 21+ variants | 633 |

This is a **descriptive association**, not evidence that having fewer variants causes higher demand.

### Business Implications

- High-volume/high-value product families can be investigated as important products within the assortment.
- Lower-volume/high-value families may warrant investigation into whether their relatively strong value contribution is being supported by sufficient transaction volume.
- Product families with many variants can be reviewed to understand whether demand is broadly distributed or concentrated among a smaller number of variants.
- Assortment decisions should also consider inventory availability, stock-outs, margin, product lifecycle, and customer preferences, which are not available in this dataset.

## 5. Seasonality & Sales Channel Insights

### 5.1 Historical Seasonality

The historical monthly analysis shows noticeable variation in transaction activity across calendar months.

The highest seasonality index is observed in:

- **June: 1.39**
- **July: 1.20**
- **May: 1.11**
- **April: 1.07**

Lower activity is observed in:

- **February: 0.82**
- **December: 0.86**
- **January and March: 0.89**

The seasonality index compares each month's average transaction volume with the overall average monthly transaction volume.

September should be interpreted carefully because the dataset contains only one complete September observation; September 2018 and September 2020 are partial months.

### 5.2 Sales Channel Mix

Channel 2 accounts for approximately **70.4% of transaction events** and **75.6% of normalized sales value**.

Channel 1 accounts for approximately **29.6% of transaction events** and **24.4% of normalized sales value**.

Channel 2 therefore has a higher normalized sales-value share relative to its transaction share.

The dataset provides channel IDs rather than verified business labels, so the analysis intentionally refers to them as **Channel 1** and **Channel 2**.

### Business Implications

- Historical transaction patterns can support **seasonal assortment and campaign planning**, particularly around the higher-activity May–July period.
- Seasonal patterns should be treated as historical observations rather than forecasts.
- Channel-level differences can be investigated further to understand differences in product mix and customer behavior.
- Channel performance should not be interpreted as causal because the available data does not identify the underlying operational differences between the channels.

## 6. Business Recommendations

### 6.1 Protect High-Value Customer Segments

Champions and highly frequent customers contribute a disproportionately large share of normalized sales value.

**Action:** Investigate retention strategies such as personalized product recommendations, early access to relevant collections, and category-specific offers for high-value customer groups.

### 6.2 Review Price Architecture

The Very High price band contributes approximately 40.1% of normalized sales value while representing only 19.7% of transaction events.

**Action:** Analyze which product categories and product families drive this value contribution and evaluate whether the current assortment has sufficient representation across price points.

### 6.3 Optimize Category Assortment

Garment Lower body and Garment Full body contribute a higher share of normalized sales value than their transaction share.

**Action:** Investigate assortment depth, product-family performance, and variant-level demand within these categories before making expansion or rationalization decisions.

### 6.4 Investigate Product Concentration

A relatively small set of product families generates substantial transaction activity.

**Action:** Identify consistently high-demand product families and investigate their variants, category placement, price positioning, and seasonal behavior.

### 6.5 Evaluate Assortment Breadth

Average transactions per variant decline as product-family variant breadth increases in this dataset.

**Action:** Use variant-level analysis to identify whether demand is concentrated among a smaller number of variants. Any assortment reduction decision should also consider inventory availability, stock-outs, product lifecycle, and margin data.

### 6.6 Use Seasonality for Planning

Transaction activity is historically stronger during May–July, with June showing the highest seasonality index.

**Action:** Use this historical pattern as an input for seasonal assortment and campaign planning, while validating it against more recent data and business events before making forecasts.

### 6.7 Improve Analysis with Additional Business Data

The current dataset supports strong descriptive analysis but does not contain several fields required for deeper commercial decision-making.

**Action:** If available, combine this analysis with actual selling price, product cost, margin, inventory, stock-outs, promotions, returns, geography, and order-level information.

This would enable more complete analysis of profitability, price elasticity, inventory efficiency, geographic demand, and campaign effectiveness.

## 7. Data Limitations & Assumptions

- The transaction `price` field is normalized. Therefore, sales-value figures are used as a **normalized sales-value proxy** and should not be presented as actual revenue in INR or another currency.
- The dataset does not provide actual product cost or margin, so profitability cannot be calculated.
- The transaction data does not contain a reliable order ID or quantity field. Therefore, the analysis refers to **transaction events** rather than unique orders or units sold.
- No verified promotion/discount flag is available, so the analysis cannot directly measure promotional effectiveness or discount elasticity.
- Sales channels are represented by numeric IDs. They are reported as **Channel 1** and **Channel 2** because their business labels were not independently verified.
- The H&M dataset does not provide suitable geographic sales information for the intended India-focused category analysis. Geographic conclusions should therefore not be inferred from this dataset.
- RFM scores are based on relative quintiles within the dataset. They represent **relative customer behavior**, not externally defined customer-value thresholds.
- RFM segments are rule-based and descriptive. They should not be interpreted as direct measures of profitability.
- September 2018 and September 2020 are partial months, so they are excluded from recurring calendar-month seasonality comparisons.
- The seasonality analysis is descriptive and historical. It does not establish causal relationships or provide a formal demand forecast.
- Portfolio classifications use median thresholds. Similar segment sizes are therefore partly a mathematical consequence of the classification method.
- Associations between price, frequency, assortment breadth, and sales value should not be interpreted as causal relationships.
- Additional business data such as inventory, stock-outs, returns, promotions, margin, product lifecycle, and geography would improve the quality of commercial recommendations.
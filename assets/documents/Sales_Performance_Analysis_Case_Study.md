# SALES PERFORMANCE ANALYSIS

### Power BI Data Analytics Case Study

**Prepared by:** Chukwuemeka David Udezue (Crafttmeal)
**Role:** Data Analyst | Business Intelligence
**Primary Tool:** Microsoft Power BI
**Supporting Tools:** Microsoft Excel, Power Query, DAX
**Dataset Period:** 3–17 January 2025

---

## 1. Project Overview

This project analyses transaction-level sales data to understand recorded sales value, transaction activity, product contribution, branch performance, and customer-type contribution.

The objective was to transform raw sales records into an interactive Power BI dashboard that supports business performance monitoring and evidence-based decision-making.

The project demonstrates data preparation, validation, KPI development, dashboard design, business analysis, and the translation of findings into practical recommendations.

## 2. Business Questions

The analysis addresses the following questions:

1. What was the total recorded sales value during the reporting period?
2. How many transactions and units were recorded?
3. How did recorded sales value differ between branches?
4. Which product contributed the largest share of recorded sales value?
5. Which customer type contributed the largest share?
6. How can management use these findings to guide further investigation?

## 3. Key Performance Indicators

| KPI                        | Verified Result |
| -------------------------- | --------------: |
| Total Recorded Sales Value |      ₦3,339,100 |
| Transaction Count          |              30 |
| Average Transaction Value  |     ₦111,303.33 |
| Total Units Sold           |             434 |

**Calculation:**

Average Transaction Value = Total Recorded Sales Value ÷ Transaction Count

₦3,339,100 ÷ 30 = ₦111,303.33

The figures represent recorded sales value. They should not be interpreted as profit because the available dataset does not contain the cost and margin information required to calculate profitability.

## 4. Data Preparation and Validation

The workflow included:

* Reviewing the transaction-level data and available fields.
* Checking the arithmetic consistency of transaction totals.
* Comparing quantity multiplied by unit price against the supplied transaction total for all 30 records.
* Defining DAX measures for the principal KPIs.
* Creating an executive overview and a performance analysis page.
* Organising visualisations to examine sales value by branch, product, customer type, and date.
* Providing branch filtering for more focused comparisons.

All 30 records passed the arithmetic consistency check.

This check does not independently prove that the source records are complete or that the original transactions are accurate.

## 5. Key Findings

### Branch Performance

| Branch     | Recorded Sales Value |    Share |
| ---------- | -------------------: | -------: |
| Masaka     |           ₦1,980,700 |   59.32% |
| New Nyanya |           ₦1,358,400 |   40.68% |
| **Total**  |       **₦3,339,100** | **100%** |

Masaka accounted for the larger share of recorded sales value during the observed period.

Further analysis would be needed to determine whether this difference relates to product availability, customer demand, transaction size, or other operational factors.

### Product Contribution

Dangote Cement recorded sales value of ₦887,500, representing approximately 26.58% of the total.

This makes it the largest product contribution identified in the verified results.

### Customer-Type Contribution

Contractors accounted for ₦1,352,400, approximately 40.50% of total recorded sales value.

This identifies contractors as the largest customer-type contributor among the verified categories.

## 6. Dashboard Structure

### Page 1: Executive Overview

The first page presents headline KPIs to help users quickly understand the overall sales position.

It includes:

* Total recorded sales value.
* Transaction count.
* Average transaction value.
* Total units sold.

### Page 2: Performance and Trend Analysis

The second page supports more detailed investigation through visualisations covering:

* Recorded sales value by branch.
* Recorded sales value by product.
* Recorded sales value by customer type.
* Sales patterns across the observed dates.
* Branch filtering.

Together, the pages provide an overview of the recorded figures and allow users to investigate differences across the available categories.

## 7. Business Recommendations

### Investigate Branch Differences

Compare stock availability, product mix, customer traffic, and transaction sizes between Masaka and New Nyanya before concluding why their recorded sales values differ.

### Monitor Leading Products

Review the availability and replenishment requirements of Dangote Cement. Include cost, gross margin, and inventory-turnover data before making purchasing decisions.

### Understand Contractor Demand

Investigate contractor order frequency, average order size, repeat purchases, and payment patterns. Use these insights to inform customer relationship and account management decisions.

### Extend the Reporting Period

Analyse additional months of data to determine whether the observed patterns persist over time.

### Introduce Profitability Measures

Incorporate purchase costs, discounts, returns, and other relevant financial fields to support gross-margin and profitability analysis.

## 8. Limitations

The findings must be interpreted within the scope of the available data.

* The dataset contains 30 transactions.
* The reporting period covers 3–17 January 2025.
* Cost and profit-margin information was not available.
* The analysis identifies patterns but does not establish their causes.
* Arithmetic consistency does not constitute an independent audit of the source data.

The results describe the supplied dataset and should not automatically be generalised to longer reporting periods.

## 9. Conclusion

This project demonstrates how Power BI can transform transaction-level records into a structured view of sales performance.

The dashboard highlights recorded sales value, transaction activity, and differences across branches, products, and customer types.

The analysis provides a starting point for further business investigation and demonstrates the importance of connecting data preparation, KPI measurement, visualisation, and business recommendations.

The next stage would be to integrate longer-period sales data, inventory information, and cost data to support deeper performance and profitability analysis.

---

**Prepared by:** Chukwuemeka David Udezue
**Professional Brand:** Crafttmeal
**Portfolio:** https://davidudezue-web.github.io/Blossom-portfolio/

**Portfolio tagline:** Visual Excellence. Data-Driven Growth.

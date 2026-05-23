
## Online Store Orders 
## Executive Summary
# Objectives

• Consolidate raw online store order records into a structured, analysis-ready dataset.

•	Perform data cleaning and quality assurance to ensure accuracy and consistency.

•	Conduct exploratory data analysis (EDA) to surface business insights.

•	Build an interactive Power BI dashboard for stakeholder reporting.

•	Document the full data pipeline, methodology, and findings for future reference.

# Scope
The project covers order transactions recorded between 1 January 2023 and 30 June 2025. The dataset encompasses 1,200 individual orders from 1,189 unique customers, spanning 7 product categories and 5 order lifecycle statuses.



## Data Cleaning & Preparation
## Cleaning Steps Applied
The following data quality operations were performed prior to analysis:

## Structural Integrity
•	Verified row count consistency: 1,200 records with no missing rows.

•	Confirmed no duplicate OrderIDs exist in the dataset.

•	Standardised column headers to PascalCase with no special characters.

## Data Type Enforcement
•	Date column parsed and cast to datetime64 format.

•	Quantity and ItemsInCart enforced as integer types.

•	UnitPrice and TotalPrice enforced as 64-bit float (decimal currency).

•	All categorical fields (Product, PaymentMethod, OrderStatus, CouponCode, ReferralSource) verified as strings.

## Value Standardisation
•	Categorical fields audited for inconsistent casing or whitespace — none detected.

•	CouponCode and ReferralSource values validated against defined enumeration sets.

•	TotalPrice cross-checked against Quantity × UnitPrice for logical consistency.

## Key Insights & Recommendations 
## High Cancellation & Return Rate
At 41.4% combined, the cancellation and return rate is significant and warrants investigation. Recommended actions:

•	Analyse cancellations and returns by product to identify high-risk categories.

•	Survey customers post-cancellation to gather qualitative feedback.

•	Review product descriptions and images to reduce expectation mismatches.

•	Consider return policy adjustments for lower-risk products.

## Instagram as Top Channel
Instagram drives the most orders (21.6%). Recommended actions:

•	Increase advertising spend and creative investment in Instagram campaigns.

•	Implement UTM tracking at SKU level to understand which products convert best via Instagram.

•	Explore Instagram Shopping integration for a seamless purchase journey.

## Diversified Payment Mix
The near-equal split across five payment methods suggests the business has already optimised for payment flexibility.

Recommended actions:

•	Ensure all payment gateways remain active and up to date.

•	Monitor Gift Card usage for potential fraud signals.

## Coupon Code Strategy
Three coupons are driving roughly equal usage. Recommended actions:

•	Track revenue impact per coupon code to measure net margin contribution.

•	Test time-limited or product-specific coupon codes to drive targeted demand.

•	Evaluate whether FREESHIP increases basket size or reduces margin.

## Laptop & Chair AOV Leadership
Laptops ($1,110.56 AOV) and Chairs ($1,098.99 AOV) generate the highest per-order revenue. Recommended actions:

•	Prioritise these categories in paid media and email campaigns.

•	Develop upsell and cross-sell strategies (e.g., Desk with Chair bundle).

•	Review whether higher-AOV items are also more prone to returns or cancellations.

## Conclusion
The Online Store Orders Data Analysis and Power BI Dashboard project successfully converted raw e-commerce transaction data into meaningful business insights and interactive visual reports. Through data cleaning, validation, exploratory analysis, and dashboard development, the project provided a clear understanding of sales performance, customer behaviour, marketing effectiveness, and order management trends.
## Screenshort
<img width="1163" height="726" alt="Online Store Orders Screenshot" src="https://github.com/user-attachments/assets/34d62f3b-ef56-447f-8a84-90991bd86e9e" />
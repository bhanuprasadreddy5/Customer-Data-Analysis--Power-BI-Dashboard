# Customer Data Analysis: Power BI Dashboard

An interactive Power BI dashboard that analyzes shopping behavior across 10 shopping malls in Istanbul (2021–2023). It looks at customer segments by gender and age, product categories, payment methods and mall locations, then turns the findings into business recommendations.

![Dashboard](images/dashboard.png)

## Project Objective

- Analyze shopping distribution by gender and find which gender bought more and generated more revenue
- Analyze shopping distribution by age group and find which age group bought more and generated more revenue
- Study how purchase categories vary across age, gender, payment method and mall
- Understand payment-method distribution and its relationship with other fields
- Visualize the data in a dashboard and give recommendations to the company

## Dataset

Shopping data from 10 malls in Istanbul, covering various age groups and genders.

| Column | Description |
|--------|-------------|
| `invoice_no` | Unique invoice ID ("I" + 6 digits) |
| `customer_id` | Unique customer ID ("C" + 6 digits) |
| `gender` | Customer gender |
| `age` | Customer age |
| `category` | Product category (Clothing, Cosmetics, Food & Beverage, Toys, Shoes, etc.) |
| `quantity` | Items purchased per transaction |
| `price` | Unit price in Turkish Lira (TL) |
| `payment_method` | Cash, Credit Card or Debit Card |
| `invoice_date` | Date of transaction |
| `shopping_mall` | Mall where the purchase was made |

## Dashboard Overview

**KPIs:** Total Revenue 101.30M | Total Customers 40K | Total Invoices 40K | Total Quantity 120K

**Visuals included:**
- Revenue, quantity and invoice count by age group
- Quantity and revenue by gender
- Category distribution by age group, payment method, shopping mall and gender
- Payment method distribution (donut chart)
- Gender distribution (donut chart)
- Payment method vs. category and vs. age group (matrix tables)

**Filters:** Age group, gender, shopping mall and invoice date

## Key Insights

- **56+ is the strongest age segment**, leading in revenue (27M), quantity (32K) and invoice count (11K).
- **Female customers** show higher quantity (about 0.18M vs 0.12M) and higher revenue than male customers.
- **18-25 is the lowest segment**, with about 15M revenue and 19K quantity.
- The 26-35, 36-45 and 46-55 groups perform similarly, at about 20M revenue and 23K quantity each.
- Category performance should be read together with age, gender, payment method and mall rather than in isolation.

## Business Recommendations

1. Build loyalty and repeat-purchase programs for the 56+ segment.
2. Use targeted category promotions to strengthen female-customer engagement.
3. Test affordable bundles and digital campaigns for the 18-25 segment.
4. Align inventory and promotions with category demand at each mall.
5. Monitor payment-method preferences by age group and category.
6. Validate dashboard measures and units before final management decisions.

## Data Validation Note

The gender charts show a quantity of 0.18M and 0.12M, while the headline total quantity is 120K. The values in this project are reported as displayed in the dashboard. The underlying measures, filters and units should be checked so the KPI cards and charts use the same definitions.

## Repository Contents

| File | Description |
|------|-------------|
| `Customer_Data_Analysis_Presentation.pptx` | 15-slide presentation of the analysis |
| `Customer_Data_Analysis_Insights_Narrative.pdf` | Written insights report and recommendations |
| `PRDA-05_customer_data_analysis.docx` | Project brief and task description |
| `images/dashboard.png` | Dashboard screenshot |

## Tools Used

- Power BI (dashboard and visuals)
- PowerPoint (presentation)

## Author

Cheemala Suresh

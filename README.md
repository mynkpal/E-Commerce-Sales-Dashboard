# Madhav Ecommerce Sales Dashboard

An interactive **Power BI dashboard** built to explore ecommerce sales
performance, profitability, product categories, customer contributions,
and payment preferences.

![Madhav Ecommerce Sales Dashboard](images/dashboard.png)

> **Dashboard preview:** Add your screenshot to the repository at
> `images/dashboard.png` so it appears here on GitHub.

## Project Overview

This project analyzes ecommerce order data using Power BI. The dashboard
brings key business metrics and trends into one place, helping users
understand sales performance across months, states, customers, product
categories, sub-categories, and payment modes.

## Dashboard Highlights

-   **KPI cards:** Total Amount, Total Profit, Total Quantity, and AOV
    (Average Order Value).
-   **Quarter slicer:** Filter the dashboard by quarter.
-   **Monthly profit/loss:** Compare positive and negative profit across
    the year.
-   **Top states:** Compare sales across leading states.
-   **Category mix:** See quantity distribution across product
    categories.
-   **Top customers:** Compare customer contribution.
-   **Payment mode analysis:** Understand the share of orders by COD,
    UPI, debit card, credit card, and EMI.
-   **Sub-category profitability:** Identify product sub-categories
    contributing most to profit.

## Key Metrics Shown

The screenshot displays these headline values:

  Metric                        Dashboard value
  --------------------------- -----------------
  Total Amount                             438K
  Total Profit                              37K
  Total Quantity                          5,615
  AOV (Average Order Value)              120.9K

*These values are transcribed from the dashboard screenshot. Confirm the
AOV measure and formatting in Power BI before using it in a formal
report.*

## Data Sources

The project uses two datasets joined by **Order ID**:

### `Orders.csv` --- 500 rows, 5 columns

  Column           Description
  ---------------- -----------------------------------------------
  `Order ID`       Order identifier used to connect the datasets
  `Order Date`     Date the order was placed
  `CustomerName`   Customer name
  `State`          Customer/order state
  `City`           Customer/order city

### `Details.project.csv` --- 1,500 rows, 7 columns

  Column           Description
  ---------------- -----------------------------------------------
  `Order ID`       Order identifier used to connect the datasets
  `Amount`         Order amount
  `Profit`         Profit recorded for the order detail
  `Quantity`       Quantity sold
  `Category`       Product category
  `Sub-Category`   More specific product grouping
  `PaymentMode`    Payment method

## Tools & Skills

-   **Microsoft Power BI** --- dashboard design and interactive
    reporting
-   **Power Query** --- data import and preparation
-   **Data modeling** --- connecting order and order-detail tables
    through `Order ID`
-   **Data visualization** --- KPI cards, bar charts, donut charts, and
    monthly profit/loss chart
-   **Business analysis** --- exploring sales, profitability, customer,
    category, and payment trends

## How to Explore the Project

1.  Download or clone this repository.
2.  Open the `.pbix` file in **Power BI Desktop**.
3.  If prompted, update the data-source paths to the included datasets.
4.  Refresh the data.
5.  Use the quarter slicer and other visual interactions to explore the
    dashboard.

## Repository Structure

``` text
madhav-ecommerce-sales-dashboard/
├── README.md
├── Madhav_Ecommerce_Sales_Dashboard.pbix
├── Orders.csv
├── Details.project.csv
└── images/
    └── dashboard.png
```

*Update the filenames in this structure to match the files you actually
upload to GitHub. Avoid uploading duplicate CSV and Excel versions
unless both are needed.*

## Business Questions This Dashboard Helps Explore

-   Which states contribute most to sales?
-   How does profit change month by month?
-   Which product categories account for the largest share of quantity
    sold?
-   Which customers contribute most to the displayed sales measure?
-   Which payment modes are most commonly used?
-   Which sub-categories generate the highest profit?

## Notes

-   The dashboard values and labels depend on the current data and Power
    BI measures.
-   Validate measure definitions, date parsing, and the relationship
    between the two tables before drawing business conclusions.
-   This is a portfolio project intended to demonstrate practical skills
    in data modeling, visualization, and exploratory business analysis.

## Author

**Mayank Pal**\
BCA Graduate \| Aspiring Data Analyst

Connect with me on [LinkedIn](https://www.linkedin.com/) and feel free
to share feedback or suggestions.

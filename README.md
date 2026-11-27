🛍️ Myntra Sales & Business Intelligence Dashboard
Interactive Retail Sales Analysis & Product Performance Report
<p align="center">
<strong>{=html}"Turning retail data into meaningful insights --- one
dashboard at a time."</strong>{=html}
</p>
<p align="center">
Author: Nensi Ray
</p>
📋 Table of Contents
- 📌 Overview
- 🎯 Problem Statement
- ✨ Key Features
- 🏗️ Project Structure
- 🔄 Dashboard Workflow
- 📊 Part A --- Business Overview
- 🛍️ Part B --- Product Analysis
- 🔍 Key Insights
- 🛠️ Tech Stack
- 📈 Results & Findings
- 🏆 Advantages
- 📷 Dashboard Screenshots
- 👤 Author
- 🙏 Acknowledgements
📌 Overview
The Myntra Sales & Business Intelligence Dashboard is a Power BI
project created to present retail sales information in an interactive
and visually organised format. It brings together product distribution,
brand performance, size-wise inventory, city-tier analysis, product
revenue details, and order distribution.

The report contains two pages:
- Overview --- a high-level summary of the business metrics and
  visual analysis.
- Product Analysis --- a separate page dedicated to
  product-focused analysis.
This project demonstrates how a dashboard can make business data easier
to explore, compare, and communicate.
Project Goals
- Understand product distribution across categories.
- Compare net revenue across brands.
- Explore size-wise inventory distribution.
- Compare sales quantity across city tiers.
- Review product-level revenue information.
- Present key information in a clean and interactive report.
🎯 Problem Statement
Retail datasets can contain large amounts of information about products,
brands, locations, inventory, and orders. Reading this information from
raw tables can make it difficult to quickly identify patterns and
compare performance.

Objective: Create an interactive Power BI dashboard that organises
the available Myntra retail data into clear visuals and a product-level
detail table, helping users explore business performance and identify
areas for further analysis.
✨ Key Features
  Feature                             Description
  📊 Product Distribution             Displays the category-wise product
mix

  🏷️ Brand Performance                Compares net revenue across brands

  📏 Size-wise Inventory              Shows inventory distribution by
size and category

  🏙️ City Tier Analysis               Compares sales quantity across Tier
1, Tier 2, and Tier 3

  📋 Product Details                  Displays product name, brand,
category, city, and net revenue

  🍩 Order Distribution               Shows the count distribution
represented in the donut chart
📑 Two Report Pages                 Separates the overview from product
analysis
🏗️ Project Structure
A suggested structure for organising the project repository:
Myntra-Sales-Dashboard/
│
├── Myntra Sales Dashboard.pbix
│
├── images/
│   ├── overview.png
│   └── product-analysis.png
│
└── README.md
Keep the Power BI .pbix file and screenshots in the folders shown
above, and update the filenames if your actual filenames are
different.

🔄 Dashboard Workflow
             START
               │
               ▼
      Retail Sales Dataset
               │
               ▼
       Data Preparation
               │
               ▼
      Power BI Report Design
               │
        ┌──────┴──────┐
        ▼             ▼
     OVERVIEW    PRODUCT ANALYSIS
        │             │
        ▼             ▼
 Product Mix      Product-level
 Brand Revenue    Performance
 Inventory        Details
 City Tier Trends
 Order Distribution
        │             │
        └──────┬──────┘
               ▼
       Explore Insights
               │
               ▼
       Business Findings
This diagram represents the report exploration flow; it does not claim
a specific data-cleaning sequence.
📊 Part A --- Business Overview
The Overview page combines multiple visuals to provide a quick
picture of the retail data. The screenshot displays a report date of
31-May-2025.
1. Product Distribution
A donut chart presents the distribution of products across categories,
including School Shoes, Jeans, T-Shirts, Sneakers, and Shirts.
- Displayed total: 17.55K
- Helps compare the relative contribution of the visible product
  categories.
2. Brand Performance
A column chart compares net revenue across brands.

  Brand        Approx. Net Revenue Shown
  Puma                             13.2M
Campus                           13.1M
HRX                              11.3M
H&M                              10.8M
Roadster                         10.0M
Adidas                            8.3M

Values are approximate readings from the chart labels in the supplied
screenshot.
3. Size-wise Inventory
A horizontal stacked bar chart displays inventory distribution by size
across product categories/brands. It helps users visually compare the
size mix and spot categories with different inventory patterns.
4. City Tier Analysis
A column chart compares the sales quantity shown for three city tiers.

  City Tier     Approx. Sales Quantity
  Tier 2                           22K
Tier 1                           16K
Tier 3                            5K

Values are approximate readings from the chart labels in the supplied
screenshot.
5. Product Details Table
The table provides a more detailed view of individual products, with
these visible fields:
- Product Name
- Brand Name
- Category
- City
- Sum of Net Revenue
The visible rows make it possible to compare product revenue alongside
brand, category, and city information.
6. Order Distribution
A donut chart displays a total count of 180K, with four visible
segments marked 25% each.

Important: The screenshot legend shows "(Blank)," "Tier 1," "Tier
2," and "Tier 3." The visual title says "Order Status Distribution," but
the displayed legend appears to contain city-tier values. Confirm the
field used in Power BI before interpreting this chart as an order-status
breakdown.
🛍️ Part B --- Product Analysis
The report includes a separate page named PRODUCT ANALYSIS for
product-focused exploration.

Use this page to present the product-level visuals and comparisons
included in your .pbix report.

Screenshot note: The supplied image shows the page tab but does not
show the Product Analysis page itself. Add a screenshot and update this
section with the exact visuals and metrics from that page rather than
assuming details that are not visible.
🔍 Key Insights
Based on the values visible in the supplied Overview screenshot:
1. Tier 2 has the highest displayed sales quantity. It is
   approximately 22K, compared with around 16K for Tier 1 and 5K for
   Tier 3.
2. Puma leads the displayed brand revenue chart. Its value is
   approximately 13.2M, closely followed by Campus at around 13.1M.
3. Adidas has the lowest displayed brand revenue among the six
   brands shown, at approximately 8.3M.
4. The product distribution visual shows 17.55K in total, providing
   a category-level view of the product mix.
5. The product table highlights individual revenue values. For
   example, the visible table lists Jeans Product 475 (Puma) at
   ₹1,31,485.29 and Lipstick Product 74 (HRX) at ₹1,30,243.83.
6. The order distribution visual displays 180K, divided into four
   equal 25% segments. Its legend should be checked because the visible
   labels appear to be city tiers rather than order statuses.
🛠️ Tech Stack
  Tool / Component                    Purpose
  📊 Microsoft Power BI Desktop       Creating and viewing the
interactive report

  📈 Data Visualisation               Presenting comparisons through
charts and tables

  🧩 Dashboard Design                 Organising report pages and visual
elements
📋 Retail Sales Dataset             Source of the product and sales
information analysed in the report
📈 Results & Findings
The dashboard brings the visible report metrics together in one place:

  Metric                                      Value Shown
  Total Net Revenue in product table     ₹29,70,28,528.60
Product Distribution                             17.55K
Order Distribution Count                           180K
Tier 2 Sales Quantity                       Approx. 22K
Tier 1 Sales Quantity                       Approx. 16K
Tier 3 Sales Quantity                        Approx. 5K
Report Date                                 31-May-2025

The dashboard makes it easier to:
- Compare revenue across the displayed brands.
- Identify the city tier with the highest displayed sales quantity.
- Explore product-category distribution.
- Review size-wise inventory patterns.
- Inspect individual product revenue records.
All figures above are transcribed from the supplied screenshot. Chart
values marked "Approx." are visual estimates from the labels.
🏆 Advantages
  Advantage                           Description
  👀 Easy to Understand               Visuals make key information easier
to read

  📊 Centralised Reporting            Multiple business views are
available in one report

  🔎 Product-Level Detail             The table provides product, brand,
category, city, and revenue fields

  ⚖️ Quick Comparisons                Brand and city-tier charts support
visual comparison

  🎨 Clear Presentation               Structured layout helps communicate
findings
📈 Decision Support                 Helps identify patterns that may
need further investigation
📷 Dashboard Screenshots
Add the report screenshots to the images folder in your repository.
1. Overview Dashboard
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/bb8db852-c1c7-4634-9e24-4f1b268e73c4" />

2. Product Analysis Dashboard
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3526d323-7403-4311-8cf5-26ea94e5aa70" />

Replace the image paths above if your screenshot filenames are
different. The current supplied screenshot shows the Overview page
only.

👤 Author
Nensi Ray

Power BI | Data Visualisation | Business Intelligence | Dashboard
Design

"Every dataset has a story --- turn the numbers into insights."
🙏 Acknowledgements
- Microsoft Power BI --- for the business intelligence and
  visualisation platform.
- Project Dataset --- for providing the retail information used in
  this dashboard.
- Learning and Practice --- this project helped develop practical
  skills in dashboard design, data presentation, and business
  analysis.

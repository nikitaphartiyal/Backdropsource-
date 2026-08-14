# Backdropsource Product & Website Performance Analysis

## 📊 Project Overview

This project analyzes **Backdropsource's product pricing and website performance** using Exploratory Data Analysis (EDA) and interactive **Power BI dashboards**.

The analysis focuses on two major product categories:

* **Shell Scheme**
* **SEG Fabric Backlit Media Displays**

The project combines product-level pricing analysis with available website traffic metrics to identify pricing patterns, customer engagement opportunities, and data-driven actions that can help improve sales.

---

## 🏢 About Backdropsource

**Backdropsource** is a global provider of customized backdrops, banners, exhibition displays, and visual branding solutions. The company offers products such as SEG displays, Shell Scheme graphics, fabric backdrops, trade-show displays, and other exhibition solutions for businesses and events.

---

## 🎯 Project Objectives

The main objectives of this project are to:

1. Analyze product pricing across different product categories.
2. Identify high-priced and low-priced products.
3. Understand the relationship between product size and price.
4. Identify pricing patterns and potential outliers.
5. Analyze website traffic and visitor engagement.
6. Identify important business KPIs.
7. Recommend data-driven actions to improve sales and conversions.
8. Build interactive Power BI dashboards for business reporting.

---

# 📁 Datasets

## 1. Shell Scheme Dataset

The Shell Scheme dataset contains:

* **24 records**
* **6 unique SKUs**
* **4 countries**
* **5 columns**

### Columns

| Column       | Description                 |
| ------------ | --------------------------- |
| Product Name | Name of the product         |
| SKU          | Unique product identifier   |
| Country      | Target market               |
| Currency     | Currency used in the market |
| Amount       | Product price               |

### Countries & Currencies

| Country   | Currency |
| --------- | -------- |
| USA       | USD      |
| UK        | GBP      |
| Australia | AUD      |
| India     | INR      |

### Key Findings

* No missing values were found.
* No duplicate records were identified.
* Product prices generally increase as product dimensions increase.
* **SS-EG-20X10** has the highest listed price across the markets.
* **SS-FULL** has the lowest listed price across the markets.
* Direct country-level price comparison requires currency conversion.
* The data shows a clear **size → price relationship**.

---

# 2. SEG Product Dataset

The SEG dataset contains **46 products** with product name, dimension, and price information.

### Columns

| Column       | Description                       |
| ------------ | --------------------------------- |
| Product Name | Name of the SEG product           |
| Dimension    | Product dimensions/specifications |
| Price        | Product price                     |

### Key Findings

* Product prices range approximately from **25.9K to 1.25M**.
* Average price is approximately **230.75K**.
* Median price is approximately **150.07K**.
* The price distribution is **right-skewed**.
* **SEG Modular Lightbox Display Kit** products represent some of the highest-priced products.
* Some dimension values are missing.
* Dimension formats are inconsistent and may include width, height, depth, or model-related specifications.
* High-priced products should not automatically be removed as outliers because they may represent genuine premium products.

---

# 🌐 Website Traffic Analysis

Available website traffic metrics were also analyzed to understand visitor engagement.

| KPI                    |  Value |
| ---------------------- | -----: |
| Daily Visitors         |    530 |
| Monthly Visits         |  16.1K |
| Pages per Visit        |   2.14 |
| Average Visit Duration |  02:05 |
| Bounce Rate            | 77.78% |

### Website Insights

* The website receives approximately **16.1K monthly visits**.
* The **77.78% bounce rate** indicates a significant opportunity to improve visitor engagement.
* Visitors view approximately **2.14 pages per visit**.
* Average visit duration is approximately **2 minutes and 5 seconds**.
* Conversion rate was not available in the provided dataset and should be included in future analysis.

---

# 📈 Power BI Dashboards

The project includes two product analysis dashboards.

## Dashboard 1 — Shell Scheme

The Shell Scheme dashboard includes:

* Total Products
* Total SKUs
* Total Countries
* Product Amount by SKU
* Country-wise Product Purchase
* Currency Distribution
* Country and SKU filters

### Main Purpose

To understand:

* Product availability across markets
* SKU-level pricing
* Country distribution
* Currency distribution
* Relationship between product size and price

---

## Dashboard 2 — SEG Fabric Backlit Media

The SEG dashboard includes:

* Total Products
* Average Price
* Minimum Price
* Maximum Price
* Median Price
* Average Price by Product
* Top Products
* Price Outlier Analysis

### Main Purpose

To identify:

* High-value products
* Price variation
* Premium product segments
* Product-level pricing patterns
* Potential price outliers

---

# 🔍 Key Business Insights

### 1. Product Size Influences Pricing

Shell Scheme products show a strong relationship between **larger display dimensions and higher prices**.

### 2. SEG Has a Wider Price Range

SEG products have significantly greater price variation, ranging from approximately **25.9K to 1.25M**.

### 3. Premium Products Drive Average Price

High-priced SEG Modular Lightbox products increase the overall average price, resulting in a significant difference between the mean and median price.

### 4. Website Engagement Needs Improvement

A **77.78% bounce rate** suggests that improving product-page experience and navigation could help convert existing website traffic more effectively.

### 5. Conversion Tracking Is Required

Traffic metrics alone cannot measure business performance. Future analysis should include:

* Conversion Rate
* Add-to-Cart Rate
* Quote Request Rate
* Revenue
* Revenue per Visitor
* Traffic Source

---

# 💡 Data-Driven Recommendations

## 1. Improve Website Conversion

Reduce the high bounce rate by improving product pages with:

* Clear **Buy Now / Get a Quote** buttons
* Product specifications
* Pricing or starting price
* High-quality product images
* Related products
* Customer reviews
* Shipping information
* Strong calls-to-action

---

## 2. Promote Premium SEG Products

High-priced SEG Modular Lightbox products can be positioned as **premium exhibition solutions**.

A tiered product strategy can be created:

**Entry Level → Mid Range → Premium**

This allows the company to target customers with different budgets while increasing opportunities for high-value sales.

---

## 3. Optimize Marketing Based on Traffic Sources

Track the complete customer journey:

**Traffic Source → Website Visit → Product View → Enquiry/Add to Cart → Conversion → Revenue**

Marketing investment should focus on channels that generate the highest **conversion and revenue**, rather than simply the highest traffic.

---

# 🛠️ Tools & Technologies

* **Python** – Data analysis and EDA
* **Pandas** – Data manipulation
* **NumPy** – Numerical analysis
* **Matplotlib / Seaborn** – Data visualization
* **Microsoft Excel** – Data preparation
* **Power BI** – Interactive dashboards
* **Power Query** – Data cleaning and transformation
* **DAX** – Power BI calculations and KPIs

---


---

# 📊 Recommended Future KPIs

For a complete sales-performance dashboard, the following KPIs should be added when data becomes available:

* **Conversion Rate**
* **Traffic by Source**
* **Revenue**
* **Revenue per Visitor**
* **Add-to-Cart Rate**
* **Quote Request Rate**
* **Product Conversion Rate**
* **Top Revenue-Generating Products**
* **Customer Acquisition Cost**
* **Return on Marketing Spend (ROAS)**

---

# 🚀 Business Impact

This analysis helps transform raw product and website data into actionable business insights.

The findings can support Backdropsource in:

* Identifying profitable product segments
* Understanding pricing patterns
* Improving product positioning
* Optimizing website engagement
* Improving conversion opportunities
* Prioritizing marketing channels
* Developing premium product strategies
* Making data-driven sales decisions
---


## 📌 Conclusion

The Backdropsource analysis demonstrates that **product pricing, product dimensions, and website engagement can be analyzed together to identify opportunities for sales growth**.

Shell Scheme products show a structured size-based pricing pattern, while SEG products provide opportunities in both mid-range and premium segments. At the same time, the high website bounce rate highlights the need to improve visitor engagement and conversion tracking.

The next step is to connect **website traffic, product engagement, conversion, and revenue data** into a single Power BI reporting framework for end-to-end sales performance analysis.

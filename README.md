# 🛒 E-Commerce Sales Analytics Dashboard

An interactive **Power BI business intelligence project** developed to analyse e-commerce sales, profit, products, customers, discounts, and regional performance.

The project transforms raw transactional data into meaningful business insights to identify **profitability trends, high-performing products, loss-making areas, regional performance gaps, and opportunities for sustainable growth.**

---

## 📌 Project Overview

This project focuses on analysing e-commerce sales data from multiple business dimensions, including products, categories, customers, regions, states, sales, profit, and discounts.

The analysis follows a complete data analytics workflow:

**Raw Data → Data Cleaning → Exploratory Analysis → Data Visualization → Power BI Dashboard → Business Insights → Recommendations**

The final dashboard provides an interactive way for users to explore business performance and support data-driven decision-making.

---

## 🧰 Tech Stack

The project was developed using:

- **📊 Power BI Desktop** – Used to create the interactive dashboard and business visualizations.
- **🔄 Power Query** – Used for data cleaning, transformation, and preparation.
- **🧠 DAX** – Used to create calculated measures, KPIs, profit margins, and analytical metrics.
- **🐍 Python** – Used for data analysis, exploration, and visualization.
- **📗 Microsoft Excel** – Used for data preparation and supporting analysis.
- **📁 File Formats** – `.pbix`, `.xlsx`, `.csv`, and `.ipynb`.

---

## 📂 Data

The dataset contains transactional e-commerce information covering:

- Order Date
- Ship Date
- Customer
- Customer Segment
- Product Category
- Product Sub-Category
- Product
- Region
- State
- Sales
- Quantity
- Discount
- Profit

The raw data was cleaned and prepared before being used for analysis and dashboard development.

---

## 🎯 Business Problem

High sales do not always translate into high profitability.

A business may generate significant revenue while experiencing losses in specific products, sub-categories, states, or discount levels. Analysing sales alone therefore does not provide a complete picture of business performance.

This project addresses questions such as:

- Which categories and sub-categories generate the most profit?
- Which sub-categories contribute to losses?
- Which regions have stronger profitability?
- How are discount levels associated with profit?
- Which customer segments contribute most to sales?
- Which states have strong sales but weak profitability?
- Where should management focus improvement efforts?

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyse overall sales and profit performance.
- Measure profitability using profit margin.
- Identify high-performing and underperforming products.
- Compare category and sub-category performance.
- Analyse regional and state-level profitability.
- Understand customer segment contribution.
- Examine the relationship between discounts and profit.
- Identify business opportunities and potential problem areas.
- Provide actionable recommendations based on data.

---

# 📊 Dashboard

The Power BI dashboard consists of **three analytical pages**.

## 1️⃣ Executive Overview

Provides a high-level view of overall business performance.

### Key Visuals

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Monthly Sales & Profit Trend
- Sales by Region
- Sales by Category
- Sales by Customer Segment
- Top Sub-Categories by Sales

### Business Question

**What is happening in the business overall?**

---

## 2️⃣ Sales & Product Performance

Provides a detailed view of product, customer, category, and geographic performance.

### Key Visuals

- Profit by State
- Category Performance
- Category / Sub-Category / Product Analysis
- Top 10 Customers
- Product-Level Performance
- Regional Performance
- Profitability Analysis

### Business Question

**Where is business performance coming from, and where are the gaps?**

---

## 3️⃣ Insights & Recommendations

The final page converts the analysis into business-focused insights and recommendations.

### Key Visuals

- Discount vs Profit Analysis
- Top 5 Sub-Categories by Profit
- Bottom 5 Sub-Categories by Profit
- Profit Margin by Region
- Key Business Insights
- Business Recommendations
- Management Takeaway

### Business Question

**What actions can management take based on the analysis?**

---

# 💡 Key Business Insights

### 💰 Overall Performance

The business generated approximately **$2.53M in sales** and **$282K in profit**, with an overall profit margin of approximately **11%** across approximately **5K orders**.

The results indicate strong revenue generation, while also highlighting the importance of monitoring profitability alongside sales.

### 💻 Category Performance

**Technology** is the strongest overall contributor to profit, while **Office Supplies** demonstrates a stronger profit margin.

**Furniture** shows comparatively weaker profitability and requires further attention.

### 🏆 High-Performing Sub-Categories

**Copiers, Phones, and Accessories** are among the strongest profit-generating sub-categories.

These areas represent potential opportunities for greater strategic focus.

### ⚠️ Loss-Making Sub-Categories

**Tables** records the largest sub-category loss at approximately **-$18K**, followed by **Bookcases** at approximately **-$3K**.

This highlights that strong sales activity does not necessarily result in strong profitability.

### 💸 Discount & Profitability

The analysis indicates an **association between higher discount levels and lower profitability**, particularly at deeper discount levels.

This suggests that discount policies should be reviewed carefully for low-margin and loss-making products.

### 🌎 Regional Profitability

The **West region** records the highest profit margin at approximately **14%**, while the **Central region** records the lowest at approximately **7%**.

This creates an opportunity to investigate the factors associated with stronger regional profitability.

---

# 🚀 Business Recommendations

Based on the analysis, the following recommendations are proposed:

### 1. Control Excessive Discounting

Review discounts above **20%**, particularly for products and markets with weak profitability.

### 2. Prioritise Profitable Products

Increase strategic focus on strong profit-generating sub-categories such as **Copiers, Phones, and Accessories**.

### 3. Review Loss-Making Products

Investigate pricing, costs, discount levels, and product strategy for **Tables and Bookcases**.

### 4. Analyse Regional Best Practices

Investigate the factors associated with the West region's stronger profitability and evaluate whether relevant practices can be applied to lower-margin regions.

### 5. Improve Loss-Making State Performance

Identify states where sales are strong but profit remains negative and review pricing, discounting, and operating factors.

### 6. Monitor Profit Alongside Sales

Track profit margin together with revenue to ensure that sales growth translates into sustainable profitability.

---

# 📈 Business Impact

This dashboard can support management and business teams by helping them:

- Monitor overall business performance.
- Identify profitable and loss-making product areas.
- Evaluate regional profitability.
- Review the effectiveness of discount strategies.
- Identify areas requiring further investigation.
- Make more informed pricing and product decisions.
- Focus resources on areas with stronger business potential.

---

# 🖼️ Dashboard Preview

### Executive Overview
![Executive Overview](https://github.com/arshpreet38933-spec/E-Commerce-Sales-Analytics-Dashboard/blob/main/Overview%20snapshot%20pg1.PNG)

### Sales & Product Performance

![Sales and Product Performance](https://github.com/arshpreet38933-spec/E-Commerce-Sales-Analytics-Dashboard/blob/main/Sales%20and%20Product%20Snapshot%20pg2.PNG)

### Insights & Recommendations

![Insights and Recommendations](
https://github.com/arshpreet38933-spec/E-Commerce-Sales-Analytics-Dashboard/blob/main/dashboard_page_3_insights.png)

---

# 📁 Project Files

| File | Description |
|------|-------------|
| `Ecommerce Dashboard.pbix` | Interactive Power BI dashboard |
| `messy data.csv` | Raw dataset used for the project |
| `Ecommerce_Cleaned_Data.xlsx` | Cleaned and prepared dataset |
| `Ecommerce_Cleaned_data.ipynb` | Python data cleaning and preparation |
| `Ecommerce_Visualization.ipynb` | Python exploratory analysis and visualization |
| `E-Commerce Dashboard insight.docx` | Business insights and recommendations |
| `Overview snapshot pg1.PNG` | Dashboard Page 1 preview |
| `Sales and Product Snapshot pg2.PNG` | Dashboard Page 2 preview |
| `Insight & Recommendation Snapshot.PNG` | Dashboard Page 3 preview |

---

# 🔍 Analytical Workflow

**1. Data Collection**  
↓  
**2. Data Cleaning & Preparation**  
↓  
**3. Exploratory Data Analysis**  
↓  
**4. KPI & Measure Development**  
↓  
**5. Interactive Dashboard Development**  
↓  
**6. Business Insight Generation**  
↓  
**7. Recommendations**

---

# 👩‍💻 Skills Demonstrated

`Data Analysis` · `Data Cleaning` · `Power BI` · `DAX` · `Power Query` · `Python` · `Excel` · `Data Visualization` · `Business Intelligence` · `Business Insights`

---

## 📌 Project Type

**Portfolio Project | E-Commerce Sales Analytics | Business Intelligence**

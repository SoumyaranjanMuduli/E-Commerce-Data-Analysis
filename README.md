# 🛒 E-Commerce Sales Analysis — Power BI

> **End-to-end e-commerce sales analysis project** on Flipkart transactional data — covering data cleaning, sales performance, category trends, regional distribution, and profitability insights through an interactive Power BI report with full documentation.

---

## 📌 Project Overview

Flipkart is one of India's largest e-commerce platforms. This project analyzes sales transaction data to help business stakeholders understand:

- Which product categories generate the most revenue and profit?
- How do sales trend across months and seasons?
- Which states and cities are the top-performing markets?
- What is the return rate and its impact on net revenue?
- Which customer segments drive the highest order value?

---

## 🗂️ Repository Structure

```
📦 flipkart-sales-analysis
 ┣ 📊 Flipkart Sales Dataset (raw data).xlsx    # Original unprocessed dataset
 ┣ 📊 Flipkart Sales Dataset.xlsx               # Cleaned and transformed dataset
 ┣ 📊 Flipkart Sales Report.pbix                # Power BI dashboard (7,289 KB)
 ┣ 📄 Flipkart Sales Report Documentation.pdf  # Full project documentation
 ┣ 📄 Problem Statement.docx                    # Business problem & objectives
 ┗ 📄 README.md
```

---

## 🔧 Tools Used

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard, data modeling, DAX |
| **Microsoft Excel** | Data cleaning and transformation |
| **Word / PDF** | Problem statement and documentation |

---

## 📦 Dataset Overview

| Column | Description |
|---|---|
| `Order ID` | Unique transaction identifier |
| `Order Date` | Date of purchase |
| `Product Category` | Category of the product sold |
| `Product Name` | Specific product |
| `Quantity` | Units sold |
| `Unit Price` | Price per unit |
| `Total Sales` | Gross revenue (Qty × Price) |
| `Discount` | Discount applied |
| `Profit` | Net profit per order |
| `Customer Segment` | Customer type |
| `State / City` | Delivery location |
| `Payment Method` | UPI / Card / COD / Wallet |
| `Return Status` | Returned / Not Returned |

---

## 📊 Dashboard Highlights

**KPI Cards**
- Total Revenue
- Total Profit
- Total Orders
- Return Rate %
- Average Order Value

**Visuals**
- Monthly sales trend (line chart — seasonal patterns)
- Revenue by product category (bar chart)
- Profit margin by category (bar / scatter)
- Sales by state — top 10 markets (horizontal bar / map)
- Payment method distribution (donut chart)
- Order volume by customer segment (bar)
- Revenue vs. discount correlation (scatter)
- Daily order trend (area chart)
- Return analysis by category (stacked bar)

**Slicers**
- Date range (month/quarter)
- Product category
- State / City
- Customer segment
- Payment method
- Return status

---

## 💡 Key Insights

- **Electronics and Mobile** categories dominate revenue but have thinner profit margins due to higher discounts
- **Festive season months** (October–November) spike sales by 2–3x compared to average months
- **Cash on Delivery (COD)** orders have a significantly higher return rate than prepaid orders
- Top 3 states account for a disproportionate share of total orders — market concentration risk
- High-discount orders consistently show lower or negative profit margins — discount strategy needs review
- A small segment of customers generates a large share of repeat orders — loyalty opportunity

---

## 📄 Documentation

Refer to `Flipkart Sales Report Documentation.pdf` for:
- Full data dictionary
- Data cleaning steps applied
- DAX measures used
- Business questions answered
- Stakeholder recommendations

---

## 🚀 How to Use

1. Open **Power BI Desktop**
2. Load `Flipkart Sales Dataset.xlsx` via **Get Data → Excel**
3. Open `Flipkart Sales Report.pbix`
4. Refresh data source if prompted
5. Read `Problem Statement.docx` for business context before exploring

---

## 👤 Author

**[Your Name]**
[LinkedIn](https://linkedin.com/in/yourprofile) · [Portfolio](https://yourportfolio.com) · [Email](mailto:you@email.com)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

*Data used for educational and analytical purposes only. Not affiliated with Flipkart.*

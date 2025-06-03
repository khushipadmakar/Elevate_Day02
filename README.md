This Power BI report provides interactive visualizations based on a retail dataset. The report helps explore sales and profitability across regions, product categories, and time periods.

## Dataset Columns

The dataset includes the following fields:

| Column Name       | Description |
|-------------------|-------------|
| `Order ID`        | Unique order identifier |
| `Order Date`      | Date when the order was placed |
| `Ship Date`       | Date when the order was shipped |
| `Ship Mode`       | Shipping method used |
| `Customer ID`     | Unique customer identifier |
| `Customer Name`   | Name of the customer |
| `Segment`         | Market segment (Consumer, Corporate, etc.) |
| `Country/Region`  | Customer's country or region |
| `City`            | Customer's city |
| `State`           | Customer's state |
| `Postal Code`     | ZIP or postal code |
| `Region`          | Sales region (e.g., West, East) |
| `Product ID`      | Unique product identifier |
| `Category`        | Product category |
| `Sub-Category`    | More detailed product classification |
| `Product Name`    | Name of the product |
| `Sales`           | Sales revenue |
| `Quantity`        | Units sold |
| `Discount`        | Discount applied |
| `Profit`          | Net profit from the sale |

---

## Visualizations Included

### 🟠 Donut Charts
- **Sum of Sales by Region**: Visualizes how total sales are distributed across different regions.
- **Sum of Profit by Region**: Shows the contribution of each region to total profit.

### 🟢 Pie Chart
- **Sum of Sales by Category**: Displays the proportion of sales contributed by each product category (e.g., Furniture, Technology, Office Supplies).

### 🔵 Bar Charts
- **Sum of Profit by Category**: Compares how profitable each product category is.
- **Sum of Profit by Date**: A time-series bar chart that displays profit trends over time (can be monthly or yearly depending on your time aggregation).

---

## 🎯 Key Insights You Can Gain

- Which **region** is generating the highest sales and profit.
- Which **category** is the most profitable.
- How **profitability trends** vary over time.
- The **impact of discounts** on sales and profit (if added in future visuals).
  

## 🛠 Tools Used

- **Power BI Desktop**
- **DAX** (for calculated fields if needed)
- **Power Query** (for cleaning and transforming data)

---

## ▶️ Getting Started

1. Open the `.pbix` Power BI file using Power BI Desktop.
2. Load or update the dataset if prompted.
3. Explore visuals using filters, slicers, and drill-through features.

---

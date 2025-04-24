# 🚴 Bike Sales Performance Analysis Using Power BI

## 📌 Project Overview

This is my first independent project after two months of learning data analytics. Using **Power BI**, I explored and visualized a bike sales dataset sourced from **Kaggle**. The dataset contains **18 columns and 113,036 rows**, covering customer demographics, transaction details, product information, and sales metrics.

---

## 🧩 Dataset Description

The dataset includes sales data for a European bike company, with the following fields:

- `Date`: Sales transaction date (mm/dd/yyyy)
- `Day`, `Month`, `Year`: Extracted date parts
- `Customer Age`, `Age Group`
- `Customer Gender`: F = Female, M = Male
- `Country`, `State`: Customer location
- `Product Category`, `Subcategory`, `Product Name`
- `Order Quantity`, `Unit Cost`, `Unit Price`
- `Revenue`, `Cost`, `Profit`

---

## ❓ Business Questions

- What is the **Total Revenue, Total Sales, Total Units Sold, Gross Profit Margin**, and **Total Customers**?
- Which are the **Top 5 Countries** by revenue and profit?
- What is the **Age and Gender Distribution** in terms of revenue?
- What are the **Monthly Revenue Trends**?
- What are the **Top 5** and **Bottom 5** products and subcategories by **Profitability**?

---

## 🧼 Data Cleaning

Performed in Power Query Editor:

- Removed duplicates (reduced rows from **113,036** to **112,036**)
- Removed unnecessary columns
- Changed data types
- Recalculated key columns using DAX:
  - `Cost = Unit Cost × Order Quantity`
  - `Revenue = Unit Price × Order Quantity`
  - `Profit = Revenue - Cost`

---

## 🧠 Data Modeling

Created a **star schema**:

- Structured data into **Fact** and **Dimension** tables
- Defined **primary keys**
- Built **relationships** between tables to enhance model integrity

---

## 📊 Exploratory Data Analysis

Using DAX measures and Power BI visualizations:

1. **KPI Cards**: Displayed Total Revenue, Units Sold, Gross Margin, etc.
2. **Top 5 Countries**:  
   - 🇺🇸 United States: $30.6M Revenue / $13.8M Profit  
   - 🇦🇺 Australia: 2nd highest
3. **Age Distribution**: Adults (35–64) generated the highest revenue
4. **Monthly Sales Trend**:
   - 📈 December: $10.1M (Highest)
   - 📈 June: $10M (2nd Highest)
5. **Product Profitability**:
   - Top & bottom 5 products and subcategories visualized
6. **Slicers**:
   - Year filter
   - Gender filter for dynamic insights

---

## 📸 Dashboard

Below is a snapshot of the interactive **Bike Sales Dashboard** created in Power BI. It displays key metrics such as Total Revenue, Profit, Units Sold, Monthly Sales Trends, Top/Bottom Products, and more — all in a clean and user-friendly layout to aid data-driven decision-making.

![Bike Sales Dashboard](https://github.com/user-attachments/assets/07419158-dda2-4224-be2b-8cf3279b7b38)

---

## ✅ Recommendations

- **Low-Performing Countries**: Germany, France, and Canada show weak profit margins. Analyze local biking/racing event seasons to optimize stock levels and marketing.
- **Inventory Planning**: Avoid overstocking bikes during racing months. Stock **repair parts** instead.
- **Regional Performance**: Consider **population density** as a factor in sales strategy.
- **Age Targeting**: Adults (35–64) drive most revenue. Invest in experienced staff to target this demographic more effectively.

---

## 🛠 Tools Used

- **Power BI** (Power Query, DAX, Visualizations)
- **CSV Dataset** from **Kaggle**
- **Data Modeling** (Star Schema)
- **Exploratory Data Analysis (EDA)**

---

## 📁 Project Status

✅ Completed  
🚀 First self-led project  
📚 Practiced data cleaning, modeling, and visualization

---

## 🙌 Acknowledgments

Special thanks to Kaggle for the dataset and the Power BI community for tutorials and support throughout my learning journey.

---

## 📬 Let’s Connect

Feel free to reach out if you’d like to collaborate or share feedback!

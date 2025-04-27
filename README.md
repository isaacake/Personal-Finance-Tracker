# 💸 Personal Finance Tracker Dashboard (Excel)
This project presents a comprehensive financial tracking dashboard created in Microsoft Excel. It consolidates Income, Expenses, and Savings into a single interactive report that helps users visualize their financial activity over time.

---

## 📖 TABLE OF CONTENT

- [Visual Preview](#visual-Preview)
- [Project Structure](#project-Structure)
- [Data Source](#data-Source)
- [Dataset Description](#dataset-Description)
- [Feature Engineering](#feature-Engineering)
- [Primary Analysis](#primary-Analysis)
- [Key Dashboard Metrics](#key-Dashbord-Metrics)
- [Dashboard Features](#dashboard-Features)
- [Tools And Techniques](#tools-and-Techniques)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

---

## 📸 Visual Preview
<img width="623" alt="Personal Finance Tracker" src="https://github.com/user-attachments/assets/1aea2328-b142-4c9d-bdc2-cf613528a289" />


---
## 📂 Project Structure

This Excel-based project follows a **3-layer architecture**:

1. **📑 Dataset Layer** (`Data` sheet): Contains raw monthly records of income and expenses
2. **📊 Pivot Analysis Layer** (`Calculations` sheet): Builds dynamic Pivot Tables for summarization
3. **📈 Dashboard Layer** (`Dashboard` sheet): Visualizes insights using charts, cards, and graphs

---

## 🧾 Datasource
The dataset was gotten from om a tutorial on youtube by Evergreen Digital Tech Solution.
https://www.youtube.com/watch?v=vlrTMK6zbw0


## 🧾 Dataset Description

The dataset used in this project captures real-life finance entries across various categories from January 2021 to October 2021:

| Column Name      | Description                                   |
|------------------|-----------------------------------------------|
| `Date`           | Date of the transaction (dd-mm-yyyy)          |
| `Type`           | Income or Expense                             |
| `Category`       | Spending/earning category (e.g. Housing, Job) |
| `Amount`         | Transaction amount                            |
| `Source`         | Platform/source of income (YouTube, Job, etc) |
| `Day`            | Weekday name (Mon, Tue, etc.) for trend analysis |
| `Month`          | Month name (Jan, Feb, etc.) for trend charts  |

---

## 🧪 Feature Engineering (Excel Formula-Based)

To enhance analysis and build insightful visualizations, we performed **feature extraction** from the raw `Date` column:

| New Column | Formula Used (in Excel) | Description |
|------------|--------------------------|-------------|
| `Month`    | `=TEXT(A2, "mmm")`       | Extracts 3-letter month name from Date |
| `Day`      | `=TEXT(A2, "ddd")`       | Extracts weekday name (Mon, Tue, etc.) from Date |

These columns are crucial for:
- **Monthly trend analysis** in bar charts
- **Weekday spending pattern** visualization
- **Grouping data** in Pivot Tables dynamically

> 🧠 These transformations allow the dashboard to stay dynamic, filterable, and timeline-aware.

---

## 🔍 Primary Analysis (Pivot Table Layer)

The `Calculations` sheet is dedicated to:
- Creating **Pivot Tables** for income and expense aggregation
- Calculating KPIs like **total income**, **total spending**, **available balance**
- Deriving **monthly** and **weekly trends**
- Feeding structured results into the dashboard using linked cells

💡 This sheet acts as the engine powering the dashboard – update the `Data` sheet, and everything auto-updates.

---

## 📊 Key Dashboard Metrics

| Metric                  | Value     |
|------------------------|-----------|
| 💰 Available Balance   | $35,249   |
| 📥 Total Income        | $65,440   |
| 📤 Total Spending      | $30,191   |
| 🧾 Max Income Source   | Data with Decisions - $50,000 |
| 🏠 Top Spending        | Housing - $9,000 |
| 📅 Max Weekly Spending | Monday - Highest |
| 📆 Max Monthly Income  | October - $5,000 |

---

## 🧩 Dashboard Features

- 💳 **Credit Card-Style Balance Card** showing available funds
- 📈 **Monthly Trends** (bar chart) for income and expenses
- 📊 **Top 5 Expense Categories** visualized as colored KPI blocks
- 🕒 **Weekly Trend Chart** to analyze weekday spending habits
- 🍩 **Income Source Distribution** with percentage-wise donut chart
- 🌘 **Dark Theme Dashboard** for a clean and modern user experience


## 🛠 Tools & Techniques

| Tool              | Purpose                                 |
|------------------|------------------------------------------|
| Microsoft Excel  | Dashboard building, charts, formulas     |
| Pivot Tables      | Data aggregation, filtering              |
| Excel Charts     | Column, Donut, Line, KPI layout          |
| Conditional Formatting | Highlighting spending levels       |
| Excel Formulas   | SUMIFS, MAX, TEXT, VLOOKUP, dynamic ranges     |
| Icons/Emojis     | Visual enhancement of sections/cards     |

---
## 💭 Insights

- ☕  Coffee Habit: Significant spending on daily coffee (5 per day) totaling ~150/month
- 🏡  Fixed Expenses:Consistent rent payments (900/month) and transport costs
- 💰  Income Streams: Primary salary (5000/month) supplemented by variable passive income
- 💸  Discretionary Spending: Regular spending on entertainment, clothes, and dining out
- ⛪  Charitable Giving: Consistent 55 donations to orphanage

---

## 👍 Recommendations

## Budget Optimization
- Reduce daily coffee expenses by 50% to save approximately **$75/month**.
- Review discretionary spending categories to identify potential savings.

## Income Enhancement
- Focus on growing **passive income streams** with strong potential (e.g., YouTube, online earnings).
- Track and analyze which passive income sources are the most profitable.

## Financial Planning
- Create a **formal budget** based on current spending patterns.
- Set **savings goals** according to the income-expense differential.
- Implement **cash flow tracking** for better financial management.

## Habit Tracking
- Monitor the frequency of small purchases (e.g., coffee, dining out) that accumulate over time.
- Identify opportunities for **bulk purchases** or more cost-effective alternatives.

## Investment Strategy
- Allocate a portion of the **$3000–$4000 monthly surplus** (after expenses) toward investments.
- Consider setting up **automated savings transfers** to ensure consistent investment.

---

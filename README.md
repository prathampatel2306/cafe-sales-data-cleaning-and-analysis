# Café Sales — Data Cleaning & Exploratory Analysis

> Data cleaning and exploratory analysis of a café sales dataset using Python (Pandas & Matplotlib), including handling missing values, data transformation, and deriving meaningful business insights.

---

## Overview

This project focuses on cleaning a messy café sales dataset and performing exploratory data analysis (EDA) to extract actionable insights about sales trends, product performance, and customer behavior. The cleaned dataset is then used to generate clear, business-relevant visualizations.

---

## Project Structure

```
cafe-sales-data-cleaning-and-analysis/
├── data/               # Raw and cleaned dataset files
├── images/             # Exported chart visualizations
├── notebook/           # Jupyter Notebook with full analysis
├── dashboard/          # Power BI dashboard files
└── README.md

```

---

## Data Cleaning Steps

The raw dataset contained several quality issues that were addressed systematically:

- Removed missing values (NaN) across key columns
- Standardized column names for consistency
- Mapped and normalized item categories
- Cleaned and formatted numerical columns (price, quantity)

---

## Analysis & Visualizations

The following analyses were performed on the cleaned dataset:

| Matplotlib Visualization | Chart Type | Purpose |
|---|---|---|
| Monthly Revenue Trend | Line Chart | Identify sales patterns over time |
| Revenue by Item | Pie Chart | Understand product contribution to total revenue |
| Quantity vs Revenue | Bar Charts | Compare volume sold against revenue generated |
| Order Value Distribution | Histogram | Analyze spread and frequency of order amounts |

| Power BI Visualization                      | Chart Type  | Purpose                                                  |
| ------------------------------------------- | ----------- | -------------------------------------------------------- |
| Key Performance Indicator (KPI)             | Cards       | Provide a quick overview of key business metrics         |
| Revenue Trend (Monthly)                     | Line Chart  | Identify sales patterns and seasonal trends over time    |
| Units Sold by Item                          | Bar Chart   | Compare product performance based on quantity sold       |
| Payment Method Distribution                 | Donut Chart | Understand customer payment preferences and distribution |
| Filters (Month, Item)                       | Slicers     | Enable interactive analysis and dynamic data exploration |
| Insight Text                                | Text Box    | Highlight key business insights and interpret trends     |


---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive development environment |
| Power BI | Dynamic Dashboard for visusalization and analysis |

---

## Outcome

The dataset was successfully cleaned and analyzed, producing clear insights into sales patterns and customer purchasing behavior. The findings from this project can support data-driven decision-making for café operations, menu planning, and revenue optimization.

---

## Getting Started

To run this project locally:

1. Clone the repository
   ```bash
   git clone https://github.com/prathampatel2306/cafe-sales-data-cleaning-and--analysis.git
   ```
2. Install dependencies
   ```bash
   pip install pandas matplotlib jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook notebook/
   ```

---

## Author

**prathampatel2306** — [GitHub Profile](https://github.com/prathampatel2306)

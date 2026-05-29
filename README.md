# 📊 USA Regional Sales Analysis — Acme Co. (2014–2018)

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?style=flat&logo=plotly&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 🧾 Overview

This project is an **end-to-end Exploratory Data Analysis (EDA)** of Acme Co.'s USA sales data spanning **2014 to 2018**. The dataset covers multiple dimensions — products, channels, customers, states, and regions — merged from 6 Excel sheets into a unified analysis pipeline.

The project concludes with an **interactive Power BI dashboard** for business decision-making.

---

## 🎯 Objectives

- Identify top-performing products, sales channels, and geographic regions
- Uncover seasonal trends and year-over-year patterns
- Segment customers by revenue and profit margin
- Spot pricing and margin risks across product categories
- Deliver actionable insights for market expansion strategy

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming language |
| Pandas & NumPy | Data cleaning and wrangling |
| Matplotlib & Seaborn | Static visualizations |
| Plotly | Interactive charts & choropleth maps |
| Jupyter Notebook | Analysis environment |
| Power BI | Business intelligence dashboard |
| Microsoft Excel | Source data (6 sheets) |

---

## 📁 Project Structure

```
usa-regional-sales-analysis/
├── EDA_Regional_Sales_Analysis.ipynb   # Main analysis notebook (15 analyses)
├── SALES_REPORT.pbix                   # Power BI interactive dashboard
├── data/
│   └── sales_data.xlsx                 # Source data (available on request)
├── assets/
│   └── screenshots/                    # Dashboard & chart previews
└── README.md
```

---

## 📊 Analysis Performed (15 Total)

| # | Analysis | Method |
|---|----------|--------|
| 1 | Monthly Sales Trend (2014–2018) | Line chart |
| 2 | Sales by Channel Mix | Bar / Pie chart |
| 3 | Top Products by Revenue | Horizontal bar |
| 4 | Profit Margin Distribution | Scatter plot |
| 5–6 | Seasonal Volume Patterns | Line chart |
| 7–8 | Regional Performance Comparison | Bar chart |
| 9 | Total Sales by US Region | Horizontal bar |
| 10 | Sales by State | Choropleth map (Plotly) |
| 11 | Top 10 States by Revenue & Orders | Dual bar chart |
| 12 | Avg Profit Margin by Channel | Bar chart |
| 13 | Top & Bottom 10 Customers | Side-by-side bar |
| 14 | Customer Segmentation (Revenue vs Margin) | Bubble chart |
| 15 | Feature Correlation Heatmap | Seaborn heatmap |

---

## 🔍 Key Findings

- 🌎 **West region dominates** with ~$360M revenue (~35% of total)
- 🏆 **California = $230M+** and 7,500+ orders — more than 2× the next state
- 🏪 **Channel split:** Wholesale 54%, Distributor 31%, Export 15%
- 💰 **Top product (Product 26):** $118M in revenue
- 📈 **Unit price is the #1 driver** — correlates 0.91 with revenue, 0.94 with cost
- ⚖️ **Profit margins consistent** across channels (~37–38%)
- ⚠️ **2017 revenue dip** to ~$21.2M — warrants further investigation

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/deogharekaruna/usa-regional-sales-analysis.git
   cd usa-regional-sales-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn plotly openpyxl jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook EDA_Regional_Sales_Analysis.ipynb
   ```

   Or open directly in **Google Colab** — no setup needed.

4. **For Power BI dashboard** — open `SALES_REPORT.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop)

> 📌 **Note:** The source Excel file is not included due to size. Contact me to request the dataset.


---

## 👩‍💻 About Me

**Karuna Deoghare** — Data Analyst passionate about turning raw data into business insights using Python, Power BI, and data storytelling.

- 🔗 **LinkedIn:** [linkedin.com/in/karunadeoghare](https://linkedin.com/in/karunadeoghare)
- 🐙 **GitHub:** [github.com/deogharekaruna](https://github.com/deogharekaruna)
- 📧 **Email:** (mailto:karudeoghare@gmail.com)

---

⭐ *If you found this project useful, consider giving it a star!*

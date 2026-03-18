# 📊 Real Estate Sales Analysis — Tableau Project

## 🌐 Live Dashboard
👉 [View on Tableau Public]-https://public.tableau.com/views/TableauMiniProject_17738135766000/Map?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
## 📋 Overview
An interactive Tableau workbook analyzing Real Estate Sales data across 
multiple US states and towns. The project explores sales distribution, 
property types, revenue trends, and geographic patterns through 9 sheets,
1 interactive dashboard, and 1 data story.

## 🗂️ Data Source
- **Dataset:** Real Estate Sales (Sheet1)
- **Format:** Excel / CSV
- **Fields Used:** Town, State, Sale Amount, Assessed Value, Sales Ratio,
  Property Type, Residential Type, List Year, Months, Sale Category

## 📊 Dashboards & Sheets

| # | Sheet Name | Chart Type | Description |
|---|---|---|---|
| 1 | Sale Distribution | Pie Chart | Distribution of sale amounts into High (42.61%), Low (40.80%), and Medium (16.59%) value categories |
| 2 | Bar Chart - Total Sale By Town | Bar Chart | Top towns by total sale amount — Hot Springs leads with ~$962M |
| 3 | YOY | Line Chart | Year-over-year sale amount trend from 2011 to 2022 |
| 4 | MOM | Line Chart | Month-over-month % difference in sale amounts across 12 months |
| 5 | Distribution of Property Types | Pie Chart | Single Family dominates at 52.24%, followed by Residential (26.03%) and Condo (9.34%) |
| 6 | Highlight Table | Table | Average Sales Ratio by Town and Residential Type across 50 towns |
| 7 | Treemap | Treemap | Sale amount breakdown by Residential Type — Single Family is the largest segment |
| 8 | Map | Geographic Map | Sales Distribution By State across the US with sale amounts per state |
| 9 | Yearly Trend | Line Chart | Yearly sale amount trend (2010–2022) filtered by State with a spike in 2020 |

## 🖥️ Dashboard 1 — Property Sales Dashboard
An interactive summary dashboard combining 5 key views in one place:
- **Sales by Residential Type** (Treemap)
- **Total Sale Amount by Town** (Bar Chart)
- **Year-over-Year Sales** (Line Chart)
- **Sales for each State** (Geographic Map)
- **Sale Distribution** (Pie Chart)

Includes interactive filters for **State**, **List Year**, **Property Type**, and **Town**
so users can slice the data dynamically.

## 📖 Story 1 — Data Story
A guided narrative walkthrough of the key findings with 5 story points:

| Story Point | Insight |
|---|---|
| 1 | Affordable Housing Drives 83% of Market |
| 2 | Hot Springs Dominates Regional Sales |
| 3 | 2020 Marks an Unprecedented Sales Peak |
| 4 | Single Family Homes Command the Market (47.17%) |
| 5 | August Delivers a Massive Sales Surge |

## 💡 Key Insights
- **Hot Springs** is the top-performing town with over **$962M** in total sales
- **42.61%** of all sales fall in the **High Value** category
- **Single Family** properties dominate with **47–52%** of total sale amount
- **Residential + Single Family** together account for over **70%** of the entire portfolio
- Sales peaked significantly in **2020** before dropping sharply in 2021–2022
- **Month-over-month** analysis shows highest growth in **Month 12 (~+50%)**
- Geographic map reveals sales spread across most US states with Texas and 
  Arkansas showing strong numbers

## 🛠️ Tools Used
- Tableau Desktop / Tableau Public
- Excel / CSV (Real Estate Sales dataset)

## 🚀 How to View Locally
1. Download `Tableau_Mini_Project.twbx`
2. Open with **Tableau Desktop** or free **Tableau Reader**
3. Navigate between sheets using the tabs at the bottom
4. Open **Dashboard 1** for the interactive summary view
5. Open **Story 1** for the guided data narrative

---
⭐ If you found this helpful, consider starring the repo!

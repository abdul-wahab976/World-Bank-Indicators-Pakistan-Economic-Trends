# 📊 Pakistan Economic Dashboard (2000–2022)

An **interactive Power BI dashboard** showcasing Pakistan’s economic and social performance using **World Bank Open Data**.  
The project combines **Python (for data extraction & preprocessing)** and **Power BI (for visualization)** to deliver actionable insights into key economic indicators over the last two decades.

---

## 🌍 Project Description

The dashboard provides a **comprehensive overview of Pakistan’s economy** from 2000 to 2022.  
It highlights macroeconomic indicators such as **GDP, trade balance, FDI, unemployment, and population trends**.  
The purpose is to enable **data-driven decision-making** for policymakers, researchers, and analysts.

Key questions answered:
- How has Pakistan’s GDP and GDP per capita evolved?  
- What are the long-term trends in exports vs imports?  
- How much FDI is flowing into the economy?  
- What are the unemployment and demographic changes?  
- Is life expectancy improving alongside economic growth?  

---

## ✨ Features

- 📈 **Economic Growth Tracking** – GDP and GDP per capita trends  
- 🌍 **Trade Balance Analysis** – Exports vs Imports across years  
- 💵 **Investment Insights** – FDI inflows and economic stability  
- 👥 **Labor Market Overview** – Unemployment fluctuations  
- 🏥 **Human Development** – Life expectancy trends  
- 📊 **Interactive Visuals** – Line charts, donut charts, bubble charts, heatmaps, KPI cards  
- 🔍 **Filters & Slicers** – Explore indicators by year and category  

---

## 📂 Data Source

All data comes from the **World Bank Open Data API**.  
The dataset covers 2000–2022 and includes:  

| Indicator Name                  | Description                            | Unit            |
|---------------------------------|----------------------------------------|-----------------|
| GDP (current US$)               | Size of economy                        | US$             |
| GDP per Capita (current US$)    | Average income per person              | US$ per person  |
| Population                      | Total population                       | People          |
| Exports of goods & services     | Total exports                          | US$             |
| Imports of goods & services     | Total imports                          | US$             |
| FDI (Net inflows)               | Foreign Direct Investment inflows      | US$             |
| Unemployment rate (%)           | % of labor force unemployed            | Percentage (%)  |
| Life Expectancy                 | Average life expectancy at birth       | Years           |

---

## 🔎 Data Extraction Process

The workflow for data collection and preparation:  

1. **Connect to World Bank API** → Using Python libraries (`wbdata`, `pandas`)  
2. **Fetch Indicators** → Economic, social, and demographic indicators for Pakistan  
3. **Transform & Clean Data** → Rename columns, remove nulls, and structure year-wise data  
4. **Export as CSV** → Store clean dataset (`worldbank_pakistan.csv`)  
5. **Load into Power BI** → Build interactive dashboards with charts, KPIs, and insights  

---

## 📸 Dashboard Preview

*(Insert a screenshot of the Power BI dashboard here)*  

---

## 📈 Insights

- Pakistan’s **GDP increased steadily** until 2018, with a slowdown afterward  
- Persistent **trade deficit**: imports have consistently exceeded exports  
- **FDI inflows** peaked in mid-2000s but declined in recent years  
- **Unemployment** has shown cyclical fluctuations  
- **Life expectancy** improved alongside a **population surge of +50M** over two decades  

---

## 🛠️ Tech Stack

- **Python** → Data pipeline (API extraction & cleaning)  
- **Power BI** → Visualization & storytelling  
- **GitHub** → Version control & project hosting  


---

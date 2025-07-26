# Natural-Disasters-PBI-

## 📁 Report Overview
Page	Title	Description
1️⃣	Global Disaster Overview	High-level summary of disaster count, death toll, and affected population across years, types, and countries.
2️⃣	Human Impact Analysis	Deep dive into the human cost—deaths, injuries, homelessness—across disaster types and top-impacted countries.
3️⃣	Economic Impact & Damage Trends	Analysis of total and adjusted economic damages caused by disasters, broken down by year, type, and country.
4️⃣	Emergency Response & International Aid	Overview of aid response, appeal declarations, and USAID/OFDA/BHA support by disaster type and country.
5️⃣	Custom Slicer Panel	Interactive filter panel to dynamically explore the report by country, disaster type, aid, declarations, and more.

## 📊 Key Visuals & DAX Measures
Sample KPIs & Cards:
Total Disasters = COUNT('EM-DAT Data'[DisNo.])

Total Deaths = SUM('EM-DAT Data'[Total Deaths])

Adjusted Damage (USD) = SUM('EM-DAT Data'[Total Damage, Adjusted ('000 US$)]) * 1000


## 📌 Features
✅ Dynamic filtering by country, disaster type, and year

🌎 Map visualizations for global disaster distribution

📈 Trend lines, decomposition trees, and matrix comparisons

🧠 Built with clean white theme and optimized for storytelling

🆘 Emphasis on Emergency Response and Aid Effectiveness

## 📂 Dataset
- < a href = "https://github.com/NehaBadole11/Natural_Disasters_PBI/blob/main/Natural%20Disasater%20%26%20Emergency%20Response.xlsx">dataset</a>
Natural Disasater & Emergency Response.xlsx

Fields include: Disaster Type, Country, Deaths, Injured, Damage (USD), Aid, Declarations, OFDA/BHA Response

## 📽️ Dashboard Overview
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f70b20c2-566d-459d-81a5-d44efb585b9d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2eb3cc85-a9e0-4c39-86e0-4de35e745253" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/03cc2c00-1430-4b63-b4dc-bcf1a60eced3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/29f63fca-fa2c-430f-9646-1d1b17bc2f19" />

## 🧠 Insights Uncovered
Which countries faced the deadliest disasters?

What types of disasters incur the highest damage?

How effective has international aid been?

What’s the response rate by OFDA/BHA across the years?

## 🧰 Tools & Technologies Used
- **Power BI Desktop (.pbix)**
- **Excel** – for the dataset
- **DAX** – for KPIs and calculated columns
- **Power Query** – for data transformation

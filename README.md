# Egyptian-Electricity-Tariff-Analysis-Bill-Prediction
End-to-end data analytics project for Egyptian electricity consumption, tariff analysis, and household bill prediction using Python, SQL Server, Power BI, and Machine Learning.
## Business Problem
Households want to understand what drives their electricity consumption and how tariff
changes affect their bills. This project analyzes consumption drivers, tariff impact,
regional usage, and grid reliability.

##  Tools
Python (Pandas, NumPy, Scikit-learn) · SQL Server · Power BI (DAX) · Streamlit

##  Workflow
1. Data cleaning (Python): removed duplicates, fixed inconsistent labels,
   handled missing values and invalid readings.
2.Data modeling (SQL Server): star schema with 1 fact table and 5 dimension tables.
3.Dashboard (Power BI): 9 interactive pages.
4. Machine Learning: model that predicts a household's bill from recent usage and household characteristics, with a GUI for interactive predictions.

## Key Insights
- Average consumption rises from ~231 kWh to ~1,059 kWh as large appliances increase from 2 to 8.
- A 15% tariff increase scenario was modeled to show the impact on bills.
- Regional usage and grid reliability were analyzed.

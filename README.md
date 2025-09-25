# ELEVATE_LABS_DA_INTERNSHIP_DAY3_TASK3
Task 4: Dashboard Design, Objective: Design an interactive dashboard for business stakeholders.

Dataset Used:- https://www.kaggle.com/datasets/shantanugarg274/sales-dataset

## ABOUT DATA
Order ID — unique alphanumeric identifier for each order or line, for example B-26776.

Amount — sales amount for the record (currency stored as numeric, e.g., 9726).

Profit — profit associated with the record (numeric, e.g., 1275).

Quantity — number of units sold (integer, e.g., 5).

Category — top‑level product group such as Electronics, Furniture, or Office Supplies.

Sub-Category — specific product type within the category, e.g., Printers, Pens, Electronic Games, Chairs, Tables.

PaymentMode — payment method used, e.g., Credit Card, Debit Card, UPI, COD, EMI.

Order Date — transaction date in M/D/YYYY format, e.g., 6/27/2023.

CustomerName — customer’s full name, e.g., David Padilla.

State — U.S. state, e.g., Florida, California, Texas, New York, Illinois, Ohio.

City — city corresponding to the state, e.g., Miami, Los Angeles, Chicago, Dallas, Buffalo.

Year-Month — derived period key in YYYY‑MM from Order Date for monthly grouping, e.g., 2023‑06

## VISUALIZATION USED:-
Range slicer for day-of-month with dual handles and input boxes (1–31).

Vertical month slicer, numeric day tiles, weekday slicer, and year slicer (chiclet/tile style).

Donut chart for Profit by Category (Office Supplies, Furniture, Electronics).

Clustered column chart for Top 3 States by Quantity (New York, California, Florida).

KPI cards showing Sum of Profit, Sum of Quantity, and Sum of Amount, plus context cards reflecting selections (e.g., April, Friday).

Dual-series line chart: Sum of Profit and Sum of Amount by Day.

Area/line chart of Sum of Profit by Year.

Combo chart (clustered columns with line and secondary axis) for Profit and Quantity by Year.

## SUMMARY 
New York leads sales volume, followed by California and Florida, while profit is almost evenly split across Office Supplies, Furniture, and Electronics with only a small gap between them. These patterns suggest demand is concentrated in a few states, but profitability is balanced across product lines.

Overall, totals show about 6.18M in sales amount, 1.61M in profit, and 13K units sold across the dataset. Profit peaks in 2022 at roughly 0.39M, then softens in 2023–2024, with 2025 currently low at 0.08M because the data only covers January–March year‑to‑date.

Profit and units both peak in 2022, then moderate through 2024, while Thursday is the strongest weekday for both profit and sales amount across the full dataset. The daily curve also shows a mid‑week high and a Friday dip, suggesting promotion and staffing should be aligned to a Tuesday–Thursday surge window.

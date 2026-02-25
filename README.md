📊 Sales Trend & Delivery Performance Analysis
📌 Project Overview

This project analyzes sales performance, delivery efficiency, and growth trends using Python (Pandas & NumPy).

The dataset includes order details, customer names, order dates, delivery dates, total sales amount, and quantity.

🛠 Tools & Technologies

Python

Pandas

NumPy

VS Code (Jupyter Notebook)

📂 Dataset Features

Order_ID

Customer

Order_Date

Delivery_Date

Total (Sales Amount)

Qty (Quantity Ordered)

🔎 Key Analysis Performed
1️⃣ Date Feature Engineering

Extracted weekday & day name

Checked month-end orders

Calculated delivery time & delivery days

2️⃣ Delivery Classification

Used pd.cut() to categorize delivery:

Fast (0–3 days)

Normal (3–5 days)

Late (5–10 days)

3️⃣ Time-Based Analysis

Fiscal Year sales using resample("YE-MAR")

Quarterly sales using resample("QE-MAR")

4️⃣ Trend Analysis

Rolling Average (3-period)

Expanding Average

Previous Month Sales (shift)

Growth Calculation (diff)

Growth Percentage

📈 Key Insights

Highest sales recorded in May (4100).

Largest sales drop observed in June (-63.41%).

Majority of deliveries were within 3 days.

Maximum delivery delay: 8 days.

Fiscal year sales (Mar-end): 7500 & 8500.

🚀 Skills Demonstrated

Data Cleaning

DateTime Handling

Feature Engineering

Time Series Analysis

Sales Growth Calculation

Business Insight Extraction

👤 Author

Hridayendu Goswami
Aspiring Data Analyst

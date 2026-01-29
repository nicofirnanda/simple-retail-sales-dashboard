📊 Simple Retail Sales Dashboard

A Python-based retail sales analysis project that explores product performance using sales data. This project demonstrates data cleaning, aggregation, and visualization to generate actionable business insights from retail transactions.

The dashboard highlights quantity sold, total revenue, and unit price comparison across products to help identify high-performing and high-value items.

Project Objectives
This project aims to answer key business questions:
Which products generate the highest revenue?
Which products are high-volume vs high-price?
How does unit price affect total revenue contribution?
Which items are potential targets for promotion or bundling strategy?

Tools & Technologies

Python
Pandas
Matplotlib
Jupyter Notebook

Project Structure
simple-retail-sales-dashboard/
│
├── data/
│   └── sales_data.csv
├── notebooks/
│   └── dashboard.ipynb
├── screenshots/
│   └── dashboard.png
├── requirements.txt
└── README.md

Dashboard Preview

Key Insights
High unit price products (e.g., premium staples) can outperform others in revenue despite lower quantity sold.
Essential goods show consistent volume but not always the highest revenue.
Several mid-priced items produce stable revenue — good candidates for bundling or upselling.
Revenue is not purely driven by quantity — price positioning matters significantly.

How to Run This Project

Clone repository
git clone https://github.com/nicofirnanda/simple-retail-sales-dashboard.git
cd simple-retail-sales-dashboard


Install dependencies
pip install -r requirements.txt


Run notebook
jupyter notebook
Open the notebook file and run all cells.

Data Description
The dataset contains sample retail sales records including:
Product name
Quantity sold
Unit price
Total revenue (calculated)
The dataset is designed for analysis and visualization practice purposes.

Possible Future Improvements
Add profit margin simulation
Add monthly / time-series trend analysis
Build interactive dashboard (Streamlit / Plotly)
Add product category grouping
Deploy as web dashboard

Author
Nico Firnanda
Aspiring Data Analyst | Python & Data Visualization
GitHub: https://github.com/nicofirnanda
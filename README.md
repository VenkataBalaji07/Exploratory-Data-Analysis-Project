
📊 **Exploratory Data Analysis (EDA) on E-commerce Data**

📌 **Project Overview**




This project performs Exploratory Data Analysis (EDA) on an e-commerce dataset. The dataset contains transaction details, including invoices, stock codes, product descriptions, quantities, prices, customer IDs, and countries.

The goal is to analyze sales trends, customer behavior, and revenue patterns, and identify any missing values or anomalies.


📂 Dataset Description

Dataset Name            : data.csv

Number of Rows & Columns: (541,909 rows × 8 columns)

Features  :

        1.InvoiceNo: Unique invoice number for each transaction

        2.StockCode: Unique product identifier

        3.Description: Product name

        4.Quantity: Number of units sold

        5.InvoiceDate: Date and time of purchase

        6.UnitPrice: Price per unit of product
      
        7.CustomerID: Unique customer identifier

        8.Country: Country where the purchase was made





**🔍EDA Approach**

1️⃣ Data Understanding & Cleaning

✔ Loaded the dataset using Pandas

✔ Checked the shape, missing values, and duplicates

✔ Converted date columns into proper datetime format


**2️⃣ Exploratory Data Analysis**


✔ Univariate Analysis: Examined the distribution of sales, prices, and quantities

✔ Bivariate Analysis: Analyzed the relationship between revenue and different features

✔ Customer Segmentation: Identified high-value customers

**3️⃣ Data Visualization**

✔ Sales Trends: Used time-series analysis for purchase behavior

✔ Top Selling Products: Identified best-performing products

✔ Geographical Insights: Sales by country

📊 Key Findings & Visualizations

**📈 Sales Insights**

✔ Total Transactions: 541,909

✔ Average Unit Price: $X.XX

✔ Top Selling Product: [Product Name]

✔ Country with Most Sales: [Country]


**📉 Customer Behavior**

✔ Most purchases were made during [Time of Day]

✔ [X]% of customers contribute to [Y]% of total revenue

**📉 Data Issues Identified**
✔ Missing values in CustomerID column

✔ Some negative quantity values indicating returns


**🛠 Technologies & Libraries Used**

Library	Purpose

pandas	Data manipulation & analysis

numpy	Numerical operations

matplotlib	Data visualization

seaborn	Statistical plots





**📌 Conclusion**

✔ The dataset provides valuable insights into customer buying behavior and sales performance.

✔ The analysis can help businesses optimize product sales and target high-value customers.

✔ Further steps could include predictive modeling or clustering for customer segmentation.


**🌟 Show Some Love!

If you like this project, please ⭐ star this repository on GitHub.

Happy Analyzing! 🚀**

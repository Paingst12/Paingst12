# Mr. Paing Soe Tun - Data Analyst Portfolio

## About

Hi, I'm Paing Soe Tun! 

I have an analytical background and over 9 years of experience in the Telecommunication Service Industry, Network Traffic analytical support, and customer service. I have developed strong expertise in network data analysis, KPI performance evaluation, statistical Data Analysis, and cross-functional coordination to achieve SLA targets.

As an NPO Engineer (Performance Analyst) at ZTE Corporation, I played a key role in customer satisfaction management. I delivered the clean data of the insightful reports to senior management and formulated strategic solutions based on performance insights.

*I was honored by ZTE Myanmar for identifying a site with zero technical issues but low user engagement, thanks to my insightful report and presentation. I successfully optimized this site to increase traffic and maximize its benefits, all without incurring extra costs. As a result, I was recognized as an Outstanding Staff member in March 2021.*

I graduated with a Bachelor of Science in Physics (2015), an AGTI in Electronics (2011), and an Advanced Technician Diploma in Electronic Engineering (2016). I also accomplished Data Analysis with Python and Databases & SQL for Data Science with Python by IBM from Coursera.

In my free time, I enjoy exploring new data analysis tools and techniques, and I am always looking for opportunities to expand my knowledge and skills. I am driven by the thrill of discovering new insights and the satisfaction of using data to solve complex problems.



This is a repository to showcase skills, share projects and track my progress in Data Analytics topics.

## Table of Contents
- [About](https://github.com/Paingst12/Paingst12#about)
- [Portfolio Projects]
  - Python
    - [Flight Price Analysis, Portfolio Project](https://drive.google.com/drive/folders/1oKJq6PJzyvE42_grjMw3FCyKBqfZh84R?usp=sharing)  
  - SQL by Python
    - [E-Commerce Data Analysis in SQL with Python, Portfolio Project](https://drive.google.com/drive/folders/1e2jt-F7WssJGoAQRFHXoHOR_0TG_4-4l?usp=sharing)
  - Excel / Google Sheets (Dashboard)
    - [Excel Network KPI dashboards, proven experiences](https://drive.google.com/drive/folders/1ex8iMwbY22s8UMFBORXdQN5xM4D7fK3B?usp=sharing)
  - Power BI
    - [Shopify, Sales Dashboard for Customer Purchase Behavior and Transaction Performance, Portfolio Project](https://drive.google.com/drive/folders/1tY-bBj9taON1gOPfbpU1yRHW__OVwzuR?usp=sharing)
    - [ElectroHub's Sale Dashboard Analysis, Portfolio Project](https://drive.google.com/drive/folders/1CD_xsJL27wXQSKJGQQZ2Oi1OrCmOySyp?usp=drive_link)
    - [Worst-Performance Site analysis (Wk-1 2021), proven experiences](https://drive.google.com/drive/folders/1_KxosSlMwRnZZPnZXVoPvU7PkYAnvs-Z?usp=sharing).
    
  

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.


### 📌 Project: Flight Price Analysis  
**Code:** [`Project: Flight Price Analysis`](https://drive.google.com/drive/folders/1oKJq6PJzyvE42_grjMw3FCyKBqfZh84R?usp=sharing)

**Goal:** Analyze flight pricing data to identify key factors influencing ticket prices and extract actionable insights. 

**Description:** The project focused on analyzing a dataset of Flight prices with stops. The dataset included Airline, Source, Destination, Total_Stops, Price, and other relevant information. The project involved loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA), analyzing the Price and Total_Stops, and duration with price.

**Skills:** data cleaning, data analysis, correlation matrices, data visualization.

**Technology:** Python, Pandas, Numpy, Seaborn, Matplotlib, SciPy.

**Results:** offer valuable insights into flight pricing trends, showing how different factors influence airfare.


### 📌 E-Commerce Data Analysis in SQL with Python

**Goal:** To examine the sales history of the store and extract insights on its performance, as well as to identify potential improvements that can be implemented.

**Code:** [`Project: E-Commerce Data Analysis in SQL with Python.ipynb`](https://drive.google.com/drive/folders/1e2jt-F7WssJGoAQRFHXoHOR_0TG_4-4l?usp=sharing)

**Description:** This project analyzes an E-Commerce dataset sourced from Kaggle to extract valuable insights into **customer behavior, supplier performance, and sales trends** through advanced data visualization techniques. 

📂 Files in This Project
- **`data/`** ➝ Contains raw CSV files:
  - `fact_table.csv` – Core transaction details
  - `customer_dim.csv` – Customer-related information
  - `item_dim.csv` – Product specifics
  - `store_dim.csv` – Store details
  - `time_dim.csv` – Transaction dates
  - `trans_dim.csv` – Transaction metadata
  
- **`ECommerce_Analysis.ipynb`** ➝ Jupyter Notebook containing the analysis with SQL by Python with pandas.
  
- **`README.txt`** ➝ This file provides documentation for the project.
  
**Skills:** data cleaning, data analysis, , data visualization.

**Technology:** SQL, Python, Pandas, Matplotlib.

**Results:** Data Cleaning and manipulation by Python, and merging 5-Dim tables(customer_dim.csv, item_dim.csv, store_dim.csv, time_dim.csv, Trans_dim.csv) with fact_table.csv on the Foreign_Key and Primary_key by SQL. Depending on data insight, used 'group by', 'join', and categorize 'case' methods, and exported data for visualization.


### 📌 Shopify, Sales Dashboard for Customer Purchase Behavior and Transaction Performance

**Goal:** To analyze Shopify sales data in Power BI to uncover meaningful insights into transaction performance, customer purchasing behavior, and long-term customer value. By designing an interactive dashboard, the objective is to help stakeholders identify patterns in revenue generation, customer retention, and engagement trends to support data-driven decision-making.

**Code:** [`Shopify, Sale Dashboard for Customer Purchase Behavior and Transaction Performance`](https://drive.google.com/drive/folders/1tY-bBj9taON1gOPfbpU1yRHW__OVwzuR?usp=sharing)

**Description:** The dataset is from Data Tutorial. 
For DAX and modeling, the formulas are given :\
- Net_Sale is the sum of 'Subtotal Price". Total_Quantity is the sum of 'Quantity'. Net_Avg_Order_value is the average of 'Subtotal Price'.
- Total_Customers is the total count of unique customers. Single-order customers are those who ordered once. Repeat customers are those who ordered more than once.
- Lifetime Value (LTV) is Net_Sale by Total_Customer. Repeat Rate is Repeat_Customer by Total_Customer. Purchase Frequency is the Distinct Count of 'Order Number' by Total_Customer.

*Business Parameter Requirements are*: Net Sales, Total Quantity, Total Customers, Repeat Customers
- Create a *Business Parameter Requirements* as a *Select measure* field to filter and view the Trend and Map bubble with the selected parameter as the title.

The project includes the following steps: data loading, EDA (exploratory data analysis), DAX (formula is given), Dynamic Trend with Bar and line chart

**Skills:** data cleaning, data analysis, data visualization, Data Modeling (using Parameter Field), and Dynamic Titles with Bar & Chart Trend and Shape Map.

**Technology:** Power BI, DAX, Power Query Editor, Visualization.


### 📌 ElectroHub's Sale Dashboard Analysis

**Goal:** To review the Sales Trend and Discounted products by year and analyze on the top/bottom 5 sales/profit/quantity by product with promotion.

**Code:** [`ElectroHub's Sale Dashboard Analysis, Portfolio Project`](https://drive.google.com/drive/folders/1CD_xsJL27wXQSKJGQQZ2Oi1OrCmOySyp?usp=drive_link)

**Description:**  An in-depth analysis of ElectroHub's sales performance, profit trends, product performance, and customer insights. Users can leverage interactive filters and visualizations to explore key business metrics and optimize decision-making.

**Skills:** data cleaning & transforming, data analysis, data visualization.

**Technology:** PowerBI, DAX, Power Query Editor, Visualization.


### 📌 Worst-Performance Site analysis (Wk-1 2021)

**Goal:** To analyze the worst-performing sites to take action and the best-performing sites.

**Code:** [`Proven Sample Project: Worst-Performance Site analysis (Wk-1 2021)`](https://drive.google.com/drive/folders/1_KxosSlMwRnZZPnZXVoPvU7PkYAnvs-Z?usp=sharing)

**Description:** The dataset contains a list of sample KPI data related to daily Telecom Site performance. In here, the dataset is not completely actual and was randomly exported from (https://mockaroo.com/). The project includes the following steps: data loading, data cleaning, EDA (exploratory data analysis), Power Query Editor, DAX (calculating Down_time_hours, Worst_KPI_sites, and so on).

**Skills:** data cleaning, data analysis, data visualization.

**Technology:** PowerBI, DAX, Power Query Editor.





## Education
Yangon University of Economics:
MBA (online),
2021 - 2025

Mandalay University of Distance Education: 
Bachelor of Science - Physics,
Dec 2011 - Dec 2015

Technological University of Meiktila:
AGTI - Electronic,
2008 - 2010


## Certificates
The best way to showcase skills is by doing and sharing your job done, but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- [Data analysis with Python](https://www.coursera.org/account/accomplishments/records/EYX5RGZIO7B4) (May 2025) (Coursera - IBM)
- [Databases and SQL for Data Science with Python ](https://www.coursera.org/account/accomplishments/records/XJ6GTXY58ONQ) (April 2025) (Coursera - IBM)
- [Data Analyst, all in one course (Python, MySQL, Statistics, PowerBI)] (Feb 2025) (Success Point Training Center)

## Contacts
- LinkedIn: [Paing Soe Tun](https://www.linkedin.com/in/paing-soe-tun-8a2717b3)
- Email: leonardping12@gmail.com

<!---
Paingst12/Paingst12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

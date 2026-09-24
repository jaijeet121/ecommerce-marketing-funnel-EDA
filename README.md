# 🛒 E-Commerce Analytics: Marketing, Funnel & Product Performance

## 📌 Project Overview
Understanding the customer journey from initial click to final checkout is critical for e-commerce growth. This project analyzes Fuzzy Factory's marketing, website, and sales data to understand why website visitors drop off and which products and campaigns actually drive revenue[cite: 3]. 

Through Exploratory Data Analysis (EDA) and SQL integrations, this project traces the customer funnel to provide practical, data-driven recommendations for improving conversions and customer retention[cite: 3].

## 🛠 Tools & Libraries Used
* **Python:** Pandas, NumPy, SciPy[cite: 3]
* **Database:** SQLite3[cite: 3]
* **Data Visualization:** Matplotlib, Seaborn[cite: 3]
* **Environment:** Google Colab[cite: 3]

## 📊 Key Business Insights
1. **Overall Conversion Benchmark:** The website currently operates at a 6.83% overall conversion rate, successfully generating 32,313 orders from 472,871 total website sessions[cite: 3]. While marketing successfully drives traffic, there is significant room for funnel optimization[cite: 3].
2. **Brand vs. Non-Brand Performance:** The "brand" marketing campaign yields the highest conversion rate at 7.79%[cite: 3]. However, the "nonbrand" campaign is the true volume and revenue engine of the business, driving over $1.35M in total sales despite a slightly lower conversion rate of 6.71%[cite: 3].
3. **Device & Monthly Trends:** Conversion rates experience clear monthly fluctuations, with distinct performance differences between users navigating the site on desktop versus mobile devices[cite: 3]. 

## 📂 Repository Contents
* `E_commerece_(EDA).ipynb`: The primary Python notebook containing the data cleaning, SQLite database creation, and exploratory visual analysis[cite: 3].
* `dataset/`: Folder containing the 6 raw CSV files used for this analysis (Orders, Products, Order Items, Refunds, Website Sessions, and Pageviews)[cite: 3].

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pip install pandas numpy scipy matplotlib seaborn`).
3. Open `E_commerece_(EDA).ipynb` in Jupyter Notebook or Google Colab and run all cells to recreate the database and visual analytics[cite: 3].

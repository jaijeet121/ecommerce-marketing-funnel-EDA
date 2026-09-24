# 🛒 E-Commerce Analytics: Marketing, Funnel & Product Performance

## 📌 Project Overview
Understanding the customer journey from initial click to final checkout is critical for e-commerce growth. This project analyzes Fuzzy Factory's marketing, website, and sales data to understand why website visitors drop off and which products and campaigns actually drive revenue. 

Through Exploratory Data Analysis (EDA) and SQL integrations, this project traces the customer funnel to provide practical, data-driven recommendations for improving conversions, optimizing marketing spend, and increasing customer retention.

## 🛠 Tools & Libraries Used
* **Python:** Pandas, NumPy, SciPy
* **Database:** SQLite3
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 📊 Key Business Insights

* **The Landing Page is the Biggest Leak:** The overall conversion rate is 6.83%. The primary issue is not traffic volume, but the top of the funnel: ~45% of visitors leave the site directly from the landing page without viewing a single product.
* **Mobile Experience is Lacking:** Desktop users convert at nearly 3x the rate of mobile users (8.50% vs. 3.09%), indicating a high-friction mobile browsing or checkout process.
* **"Nonbrand" Drives Revenue:** The "nonbrand" campaign is the business's revenue engine, generating $1.35M in sales. Conversely, the "pilot" campaign is failing with a 1.08% conversion rate and only $3,743 in sales.
* **Cart Abandonment has Plateaued:** 66% of users who add items to their cart abandon it. While past optimizations lowered this from 77%, the rate has remained stagnant (64–67%) since 2013, requiring new intervention.
* **Single-Item Orders Dominate:** 76% of all orders contain only one item, leaving cross-selling highly untapped. The most successful product pairing is "The Original Mr. Fuzzy" + "The Hudson River Mini Bear".
* **Top Product = Biggest Refund Risk:** "The Original Mr. Fuzzy" drives the majority of gross sales ($1.21M) and net profit ($677K), but its 5.11% return rate creates the largest dollar-value refund exposure ($61,838). 
* **Critical Retention Gap:** Only 1.9% of customers make a second purchase. While 16.6% of sessions are from returning visitors, they convert at very low rates. Fixing "return visits" alone won't fix retention; the leak between *browsing again* and *buying again* must be addressed.
* **Weekend Slump:** Sales volume drops by more than 50% on Saturdays and Sundays compared to weekdays.

## 📂 Repository Contents
* `E_commerece_(EDA).ipynb`: The primary Python notebook containing the data cleaning, SQLite database creation, and exploratory visual analysis.
* `dataset/`: Folder containing the 6 raw CSV files used for this analysis (Orders, Products, Order Items, Refunds, Website Sessions, and Pageviews).
* `dataset.zip`: A compressed version of the raw datasets to accommodate GitHub's file size limits.

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pip install pandas numpy scipy matplotlib seaborn`).
3. Extract the `dataset.zip` folder so the CSV files are available.
4. Open `E_commerece_(EDA).ipynb` in Jupyter Notebook or Google Colab and run all cells to recreate the database and visual analytics.

# Ferns N Petals (FNP): Strategic Growth & Sales Analytics Dashboard

## 📌 Project Overview
This project transforms 1,000+ raw sales records into a professional 3-page interactive Power BI suite. The analysis focuses on identifying high-value regional markets, seasonal revenue drivers, and product price elasticity for **Ferns N Petals (FNP)**.

## 📊 Key Business Insights
* **Festive Seasonality:** Identified significant revenue peaks in **August (₹737K)** and **February (₹705K)**, directly correlating with Raksha Bandhan and Valentine's Day.
* **Product Strategy:** Utilized a Scatter Plot to identify "Colors" as a premium-volume leader, maintaining high demand (800 units) at a **₹1,200** average price point.
* **Regional Efficiency:** Developed a custom **Average Order Value (AOV)** measure. Analysis revealed that **Machilipatnam** reaches the highest AOV at **₹4,689**, highlighting it as a premium hub.
* **Customer Demographics:** The data shows a balanced gender split, with men contributing **50.84%** of total revenue.

## 🛠️ Technical Challenges & Solutions
* **Challenge: Identifying Price Sensitivity:** Standard bar charts failed to show how price affected volume across different categories.
* **Solution:** Implemented a **Category Scatter Plot** to visualize price elasticity, allowing for the identification of "sweet spot" pricing for top-tier products.
* **Challenge: User Experience & Navigation:** Managing deep-dive filters across three separate pages often leads to a disjointed user experience.
* **Solution:** Leveraged **Synced Slicers** (City) across all pages, ensuring that a filter applied on the Executive Summary persists through the Product and Geographic views.

## 📖 Data Dictionary
* **Total Revenue:** The sum of all successful transactions after data cleaning and deduplication.
* **Average Order Value (AOV):** A custom DAX measure calculated as `Total Revenue / Total Orders`.
* **Occasion:** The categorical label for sales events (e.g., Anniversary, Raksha Bandhan) used to track seasonal surges.

## 🛠️ Technical Stack
* **Power BI:** Advanced DAX, Data Modeling, and Synced Slicers.
* **Python (Pandas/NumPy):** Used for initial Exploratory Data Analysis (EDA) and data validation.
* **Excel:** Initial data structuring and pivot testing.

## 📈 How to Interact with this Dashboard
1. **Global City Filtering:** Use the **City Slicer** (top-left) on any page to dynamically update the entire report for a specific region.
2. **Cross-Visual Filtering:** Click on any segment of the **Sales Mix Pie Chart** (Page 1) to filter the revenue trends by a specific occasion like "Raksha Bandhan" or "Valentine's Day".
3. **Category Deep-Dive:** Click on a bubble in the **Product Scatter Plot** (Page 2) to see specific performance metrics for that category.
4. **Geographic Comparison:** Use the **Top 15 Cities Table** (Page 3) to compare localized performance against the national Average Order Value (AOV).

## 📂 Repository Contents
* `FNP_Strategic_Dashboard.pbix`: The master Power BI file with all DAX measures and models.
* `FNP_Analysis_Report.pdf`: A high-resolution, author-signed export of the 3-page dashboard.
* `Dataset/`: Cleaned sales data used for the analysis.
* `LICENSE`: MIT License.

## 👤 Author
**Lipi Virmani**
* **MBA (Business Analytics)** | Amity University Online
* **B.Tech (Computer Science)** | Maharaja Agrasen Institute of Technology
* [LinkedIn](www.linkedin.com/in/lipi-virmani)
  
